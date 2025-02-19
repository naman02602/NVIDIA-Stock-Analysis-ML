# NVIDIA Stock Analysis and Prediction Using Machine Learning and Financial Models

## Project Overview
This project aims to analyze NVIDIA's stock performance, compare it with competitors, and predict future returns using various machine learning and financial models. The analysis includes exploratory data analysis (EDA), feature engineering, and the application of predictive models such as CAPM, ARIMA, Fama-French, and GARCH.

## Table of Contents
- Project Overview
- Data Sources
- Installation
- Usage
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building and Evaluation
- Results
- Conclusion

## Data Sources
- **Yahoo Finance**: Historical stock data for NVIDIA and its competitors (AMD, INTC, QCOM).
- **FRED API**: Economic indicators from the Federal Reserve Economic Data.

## Exploratory Data Analysis (EDA)
- **Descriptive Statistics**: Summarizes key statistics of NVIDIA stock data.
- **Candlestick Chart**: Visualizes the stock's open, high, low, and close prices over time.
- **Trend Analysis**: Plots trends for different stock metrics (Open, High, Low, Close, Adj Close, Volume).
- **Volume Analysis**: Analyzes trading volumes on yearly, monthly, and weekly bases.
- **Returns Calculation**: Calculates and plots daily returns.
- **Kernel Density Estimation**: Estimates the probability density of adjusted closing prices.
- **Competitor Analysis**: Compares NVIDIA's stock performance with competitors (AMD, INTC, QCOM).

## Feature Engineering
- **Lagged Returns**: Creates lagged features to capture the effect of past returns on future performance.
- **Momentum Factor**: Calculates momentum based on the sum of past returns over a lookback period.

## Model Building and Evaluation
- **CAPM (Capital Asset Pricing Model)**: Predicts NVIDIA returns using market factors.
- **ARIMA (Autoregressive Integrated Moving Average)**: Uses ARIMA with exogenous variables to predict returns.
- **Fama-French Three-Factor Model**: Predicts returns using three Fama-French factors (Market, SMB, HML).
- **GARCH (Generalized Autoregressive Conditional Heteroskedasticity)**: Models and predicts stock price volatility.

## Results
- **Model Performance**: Compares RMSE and R-squared values across CAPM, ARIMA, and Fama-French models.
- **Volatility Prediction**: Assesses the GARCH model's ability to predict stock price volatility.

## Conclusion
This project demonstrates the application of machine learning and financial models to analyze and predict stock performance. The insights gained from this analysis can be used for risk management, portfolio optimization, and investment strategies.
