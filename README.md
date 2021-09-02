# superstore dataset
OBJECTIVE : FORECASTING FURNTIURE SALES FOR THE RETAIL STORE

In This Model We are checking the Stationarity of the Model and then using ARIMA AND SARIMA for geting the conclusion.

ARIMA - Auto Regressive Integrated Moving Average and is a way of modeling time-series data for forecasting. ARIMA can analyse data with a trend.

it is specified by three order parameters (p,d,q):

AR(p): pattern in the data showing growth/decline.

I (d): rate of change of the growth/decline.

MA (q): it shows the noise between time points.

SARIMA is stand for seasonal ARIMA.

SARIMA (Seasonal ARIMA) is basically an extended version of ARIMA model that gives the seasonal element of the time series. While, SARIMA supports data with both trend and seasonality. Besides the three order parameters of autoregression, difference, and moving average, but in SARIMA this considers the fourth parameters as seasonal periods. 

Fianally we get Mean Squared Error and Root Mean Squared Error of our forecasts.
