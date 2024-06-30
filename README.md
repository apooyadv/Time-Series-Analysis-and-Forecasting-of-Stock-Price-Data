# Time Series Analysis and Forecasting of Stock Price Data

## Overview

This repository contains my project on Time Series Analysis and Forecasting of Apple Inc.'s stock prices, conducted at the Indian Statistical Institute (ISI), Kolkata. The project explores various statistical and machine learning models to analyze historical stock price data and make future predictions.

## Project Components

### EDA (Exploratory Data Analysis)

- **AAPLEDA.ipynb**: Jupyter Notebook focusing on exploratory data analysis of Apple Inc.'s stock price data. It includes data loading, cleaning, visualization, statistical summaries, correlation analysis, and volatility assessment.

### Time Series Decomposition

- **TSDecomposition.ipynb**: Jupyter Notebook performing time series decomposition on the stock price data to extract trends, seasonality, and residual components.

### Model Selection

- **ModelSelection.ipynb**:
  
  - **ARIMA_Model**: Implementing the ARIMA (AutoRegressive Integrated Moving Average) model for time series forecasting.
    
  - **GARCH_Model**: Applying the GARCH (Generalized Autoregressive Conditional Heteroskedasticity) model to analyze and forecast volatility in stock prices.
    
  - **LSTM_Model**: Utilizing LSTM (Long Short-Term Memory) networks for deep learning-based time series forecasting.
    
  - **Prophet_Model**: Using Facebook Prophet, a forecasting tool, to predict future stock prices based on historical trends.

## Usage

To use these notebooks:
- Clone the repository to your local machine.
- Navigate to each directory (EDA, TS Decomposition, Model Selection).
- Open the notebooks using Jupyter Notebook or Jupyter Lab.
- Execute each cell to run the analyses, visualize results, and understand the methodologies used.

## Dependencies

Ensure you have the following Python libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- yfinance
- sklearn
- arch
- pmdarima
- statsmodels
- tensorflow
- prophet

## Contributors

- **Apoorv Yadav** - Student at IISER Bhopal
- **Sruba Sarkar** - Project Guide

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/apooyadv/Time-Series-Analysis-and-Forecasting-of-Stock-Price-Data/blob/main/LICENSE) file for details.
