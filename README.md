# MDSProject
Modern Database System Project

TOPIC : Web scraping stock data of Neyveli India Limited (NLCINDIA) from Yahoo Finance for storing it in InfluxDB, querying and forecasting the prices of the stock for the upcoming days.

PROGRAMMING LANGUAGE USED: Python

STEPS: 
1. Web Scraping data from Yahoo Finance.
2. Since stock data is time series data, it is inserted into InfluxDB, which is a time series database.
3. Data is queried and forecasted using the following models:
   1. Autoregressive integrated moving average (ARIMA) 
   2. Long Short Term Memory (LSTM)
4. Smoothing using Moving Average to identify trends in the stock.
5. Risk analysis was done on the stock by finding the Sharpe ratio of the stock.


