# Unit_10_homework
Completed two main activities to analyze the historical exchange value of Dollars to Yen. The first being a Time-Series Forecast and the second was a Linear Regression Forecast.
### Time-Series Forecasting
Completed the exercise including the following steps:
1. Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
2. Forecasting Returns using an ARMA Model.
3. Forecasting the Settle Price using an ARIMA Model.
4. Forecasting Volatility with GARCH.
#### Results
1. Based on your time series analysis, would you buy the yen now? 
    - Yes, because it is going up
1. Is the risk of the yen expected to increase or decrease?
    - risk seems to be going down
1. Based on the model evaluation, would you feel confident in using these models for trading?
    - Not sure, as this is very basic and using past information only to predict future performance

### Linear Regression Forecasting
Completed the exercise including the following steps:
1. Data Preparation (Creating Returns and Lagged Returns and splitting the data into training and testing data)
2. Fitting a Linear Regression Model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.

#### Results
Use the results of the linear regression analysis and modeling to answer the following question:

1. Does this model perform better or worse on out-of-sample data compared to in-sample data?
    - It is hard to say. The out-of-sample does have a lower Root Mean Squared Error, but that may mean that it has been overfitted. They are both very low, and seem to be pretty close. 