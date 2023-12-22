# Timeseries-Forecasting
LSTM Timeseries forecasting on weather data

# Important
1) The files 'predictions.ipynb' and 'features.ipynb' constain the working models of univarirate and multivariate forecasting models on the weather database, gathered from 'www.visualcrossing.com'.
2) The multivariate model requires inverse transformation of the output data. (Data was standardized to 1 std div)
3) Other files contain various methods of forecasting, using various methods like including the cos function of the month/year time series values as a feature, to highlight the seasonality of the data (Not usefull in stock prediction, but useful for seasonal data like weather parameters)
4) Financial data was mostly gathered from yfinance API.

# Dependencies 

Refer requirements.txt

Use (pip3 or pip) install -r requirements.txt

# Python version used in all projects -> 3.9.0


