📈 Stock Price Forecasting Dashboard (NVDA)

Overview



This project analyzes and forecasts NVIDIA (NVDA) stock prices using ARIMA time-series modeling in R. The dashboard provides historical price analysis, stationarity testing, model diagnostics, residual analysis, and 30-day forecasts through an interactive Flexdashboard.



Project Objective



The goal of this project is to apply time-series forecasting techniques to financial market data and evaluate the effectiveness of ARIMA models for stock price prediction.



Features

Historical NVDA stock price visualization

Augmented Dickey-Fuller (ADF) stationarity testing

Differencing analysis

ACF and PACF diagnostics

Automatic ARIMA model selection

Residual diagnostics and Ljung-Box testing

30-day stock price forecasts

Interactive visualizations using Plotly

Methodology

1\. Data Collection

Downloaded NVIDIA (NVDA) stock price data from Yahoo Finance using quantmod.

2\. Stationarity Testing

Applied the Augmented Dickey-Fuller (ADF) test.

Determined the number of differences required to achieve stationarity.

3\. ARIMA Modeling

Used auto.arima() to identify the best-fitting model.

Selected model: ARIMA(5,2,0).

4\. Diagnostic Analysis

Examined ACF and PACF plots.

Evaluated residuals using the Ljung-Box test.

5\. Forecasting

Generated 30-day forecasts with confidence intervals.

Visualized forecast uncertainty using interactive charts.

Key Findings

NVDA prices were non-stationary and required differencing.

The selected model was ARIMA(5,2,0).

Residual diagnostics indicated that additional model refinement may improve forecast performance.

Forecasts demonstrate both expected price movement and uncertainty ranges.

Tools Used

R

Flexdashboard

Plotly

Forecast

Tseries

Quantmod

Dplyr

GitHub Pages

Repository Contents

index.html — Published dashboard

Version\_1\_fixed.Rmd — Source code

README.md — Project documentation

Future Improvements

Log-price modeling

Random Forest forecasting

XGBoost forecasting

Model comparison using RMSE and MAE

Integration of company fundamentals (EPS, Revenue, Earnings)

Author

test

Alex Alvarez

Economics Student | Data Analytics | Time-Series Forecasting

