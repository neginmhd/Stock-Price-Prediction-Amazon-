## Stock Market Prediction using ARIMA time series model
Recently stock marcket prediction using AI models increased.
This means that use the AI models to extract trends and essential features that specifies the company’s stock performance.
In this repository we use the ARIMA model for predict stock marcket prediction.
For find best hyperparameters of model, we use auto_arima module from pmdarima python library.

## Introduction
Auto-Regressive Integrated Moving Average or ARIMA for short is a learning algorithm for pridict time series dataset.
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
In this case we use "AMAZON" market data for train and evaluate ARIMA model from "2016-1-1" to "2020-12-31".
We use the last 60 records for evaluate model and other records in dataset for train.
In this case we use "close" values for train and evaluate ARIMA model.
