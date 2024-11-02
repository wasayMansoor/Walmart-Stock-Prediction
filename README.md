# Walmart Stock Analysis

## Overview

This project provides an end-to-end workflow for analyzing historical stock price data and predicting future prices using machine learning. Leveraging a dataset of historical stock prices, we aim to uncover key insights into trends and volatility, and to develop models that predict future prices with reasonable accuracy. This repository includes everything from data preprocessing and exploratory data analysis to the development and evaluation of various machine learning models.

This repository includes:

- Exploratory data analysis
- Data visualization
- Machine learning models for predictions
- Performance evaluation of models

## Dataset

The dataset used in this project, WMT.csv, is obtained from kaggle. It contains key financial metrics for each day, structured as follows:

- **Date**: Date of the trading day
- **Open**: Opening price
- **High**: Highest price of the day
- **Low**: Lowest price of the day
- **Close**: Closing price of the day
- **Adj Close**: Adjusted closing price (after stock splits, dividends, etc.)
- **Volume**: Number of shares traded

## Features

The main features of this project include:

1. **Data Preprocessing**: Handling missing values, feature engineering, and scaling
2. **Data Visualization**: Insights into historical trends, daily and monthly volume, price movements
3. **Machine Learning Models**:
   - Linear Regression
   - Random Forest Regressor
   - K-Nearest Neighbors (KNN)
4. **Model Evaluation**: Performance metrics including Mean Squared Error and R-squared for each model
