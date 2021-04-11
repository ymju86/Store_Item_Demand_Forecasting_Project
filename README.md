# Store Item Demand Forecasting Project
Data: https://www.kaggle.com/c/demand-forecasting-kernels-only/data?select=train.csv
- pandas, numpy, matplotlib, plotly, sklearn, tensorflow, keras

Use Keras (TensorFlow) to implement LSTM (Long Short-term Memory)
-	Data Wrangling
-	Data Transformation to make it stationary and supervised
-	Building the LSTM model & evaluation

--------------------------------------------------------------------------------------
Time series forecasting is an important area of Machine Learning because there are so many prediction problems that involve a time component. There are many methods in the literature to achieve this like Autoregressive Moving Average (ARMA), Autoregressive Integrated Moving Average (ARIMA), Seasonal Autoregressive Integrated Moving-Average (SARIMA), Vector Autoregression (VAR), and so on.

## Data Transformation

To model our forecast easier and more accurate, the transformations below are needed:

* Convert the data to stationary if it is not
* Convert from time series to supervised for having the feature set of our LSTM model
* Scale the data

First off, how do we check if the data is not stationary? Let’s plot it and see:

