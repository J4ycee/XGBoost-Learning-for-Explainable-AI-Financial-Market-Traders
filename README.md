# XGBoost Learning for Explainable AI Financial Market Traders
This project is for the graduation project in MSc Data Science at the University of Bristol

In recent decades, the stock market has gradually prospered as people's incomes have increased in general. Its nature of high returns has attracted a large number of investment institutions and individual investors to engage in the stock market, and its increasingly irreplaceable role in economic development has also drawn a number of scholars to carry out various studies in the hope of exploring ideal models and feasible methods for the prediction of stock market-related issues. Moreover, the rapid development of artificial intelligence has led to the promotion of the theory of machine learning as well, which has been widely used in various practical applications including the field of stock market and has resulted in a boom in machine learning.

This research is based on the study by Wray, Meades and Cliff (2020) on a DeepTrader model created based on the Long Short-Term Memory (LSTM) algorithm for predicting the behaviour of stock traders. The input data used to train the DeepTrader model in this study comes from the limit order book (LOB) of the secondary market, and the model does not provide an explicit prediction of future price of the stock. Instead, the expected output of the model is the price at which the traders do trading behaviour, thus allowing the system to behave like a trader and issue specific quotes (bid or ask) based on specific LOB conditions. The data for this study is taken from Bristol Stock Exchange (BSE), a virtual stock exchange, which contains data such as trader IDs, stock prices, quotes, etc. (Additional content to be added when the dataset is available.)

On the basis of the above, this study explores a DeepTrader model based on another algorithm, XGBoost, and compares the predictive effects of two DeepTrader models based on DLNN and XGBoost on the behaviour of stock traders respectively on various dimensions including balanced group test (BGT), Average profit per trader (APPT) and explainability. The results show that the LSTM-based DeepTrader trader model performs better than the XGBoost model in general, but the model has a high upper bound and a weak lower bound, making it less stable than the XGBoost model.
