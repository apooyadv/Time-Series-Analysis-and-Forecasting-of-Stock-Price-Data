##  Model Selection Notebook

This repository contains code and documentation for analyzing and forecasting stock prices, focusing on Apple Inc. The project explores various time series models to predict stock prices and evaluates their performance.

## Models Implemented

### ARIMA Model

The AutoRegressive Integrated Moving Average (ARIMA) model is implemented to capture temporal dependencies and forecast stock prices.

- **Hyperparameters**: Includes parameters like `p` (autoregressive order), `d` (differencing order), and `q` (moving average order) optimized through grid search or data characteristics.

### GARCH Model

The Generalized Autoregressive Conditional Heteroskedasticity (GARCH) model is used to analyze volatility clustering in stock returns.

- **Hyperparameters**: Parameters such as `p` (order of the GARCH term) and `q` (order of the ARCH term) are optimized based on model fit and volatility characteristics.

### LSTM Model

A Long Short-Term Memory (LSTM) neural network is employed to capture complex temporal dependencies in stock price data.

- **Hyperparameters**: Includes settings like number of LSTM units and epochs.

### Facebook Prophet Model

The Prophet library by Facebook is utilized for time series forecasting with additive seasonality.

- **Hyperparameters**: Prophet parameter specific seasonality (`weekly_seasonality`, `yearly_seasonality`, `daily_seasonality`) is adjusted for accurate forecasts.

## File Description

### `ModelSelection.ipynb`

The `ModelSelection.ipynb` notebook in this repository implements and evaluates the above models. It includes:

- Data preprocessing steps specific to each model.
- Training and evaluation of models using historical stock price data.
- Visualization of model forecasts compared to actual stock prices.
- Metrics and analysis to compare the strengths and weaknesses of each model.

This notebook serves as a comprehensive guide to selecting and applying different time series models for forecasting stock prices, providing insights into their applicability and performance characteristics.

### Usage

To use this notebook:
- Clone the repository and navigate to the Mdel Selection directory.
- Open ModelSelection.ipynb using Jupyter Notebook or Jupyter Lab.
- Execute each cell to load, clean, visualize, and analyze the data as described.

### Dependencies

Ensure you have the following Python libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- yfinance
- sklearn
- tensorflow
- pmdarima
- arch
- prophet

### Contributors

- **Apoorv Yadav** - Student at IISER Bhopal
- **Sruba Sarkar** - Project Guide

### License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/apooyadv/Time-Series-Analysis-and-Forecasting-of-Stock-Price-Data/blob/main/LICENSE) file for details.
