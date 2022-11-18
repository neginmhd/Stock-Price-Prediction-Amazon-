## Stock Price Prediction using ARIMA model
ARIMA model is one of the most efficient approaches that one can use for time series forecasting.
The ARIMA model has been widely utilized in banking and economics since it is recognized to be reliable, efficient, and capable of predicting short-term share market movements.
In this repository we will be using the ARIMA model to forecast the prices of Amazon Inc
To find the best hyperparameters of model, we use auto_arima module from pmdarima python library.

## Introduction
Auto-Regressive Integrated Moving Average(ARIMA) is a learning algorithm for pridict time series dataset.
This algorithm is generated through some parts which can be described as:
AR — auto-regression: term created based on historical data points.
I — integration: term for overall "trend" in the historical data points.
MA — moving average: term of error based on historical data points.

## Prerequisites
Our code is based on Python3, and we use libraries as follows:
1. numpy
2. pandas
3. sktime
4. pmdarima

## Dataset
The dataset extract from yfinance python library for Download market data from Yahoo.
In this case we use "AMAZON" market data to train and evaluate ARIMA model from "2016-1-1" to "2020-12-31".
We use the last 60 records to evaluate model and other records in dataset to train.
In this case we use "close" values for train and evaluate ARIMA model.
