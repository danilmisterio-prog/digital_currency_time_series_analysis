# Cryptocurrency Time Series Forecasting

## Project Overview

This project analyzes cryptocurrency market data and applies time series forecasting techniques to predict future price movements.

The analysis includes exploratory data analysis, stationarity assessment, autocorrelation analysis, and the development of several forecasting models.

## Tools Used

* Python
* Pandas
* Matplotlib
* Statsmodels
* pmdarima

## Methods Applied

### Exploratory Data Analysis

* Descriptive statistics
* Monthly aggregation
* Trend visualization

### Time Series Analysis

* Stationarity testing (ADF Test)
* Autocorrelation Function (ACF)
* Residual diagnostics

### Forecasting Models

* AR(1)
* Naive Forecast
* ARIMA
* ARIMAX

## Model Evaluation

Models were evaluated using:

* MAE
* RMSE
* MAPE
* Residual analysis
* Ljung-Box test
* Jarque-Bera test

## Key Findings

* The cryptocurrency exhibited strong long-term growth.
* ARIMA outperformed simpler benchmark models.
* Residual diagnostics indicated improved model adequacy compared to the naive forecast.
* Incorporating trading volume as an exogenous variable provided additional forecasting information.

## Repository Contents

* `cryptocurrency_forecasting.ipynb` – full analysis notebook
* `digital_currency.csv` – dataset
* `README.md` – project documentation
