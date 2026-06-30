# USD Price Forecasting using Ensemble Machine Learning Models

## Overview

This project investigates the use of ensemble machine learning techniques for forecasting the next-day closing price of the US Dollar using historical financial data.

The workflow includes data acquisition from Yahoo Finance, time series preprocessing, sliding-window feature generation, ensemble learning, and performance comparison between multiple regression models.

## Dataset

Historical exchange rate data were downloaded directly from Yahoo Finance using the `yfinance` Python library.

The dataset contains daily observations including:

- Date
- Open
- High
- Low
- Close

The analysis covers the most recent five years of historical market data.

---

## Project Workflow

### Data Collection

- Download historical USD exchange rate data using `yfinance`
- Remove unnecessary columns
- Explore the dataset

### Exploratory Data Analysis

- Interactive time series visualization using Plotly
- Stationarity discussion
- Financial time series analysis

### Data Preparation

- Chronological train-test split
- Sliding window (timeframe) generation
- Feature reshaping for machine learning models

### Machine Learning Models

The following regression models were implemented and compared:

- Linear Regression
- Random Forest Regressor
- Bagging Regressor
- Stacking Regressor

Performance was evaluated using Mean Absolute Error (MAE).

### Feature Engineering

Additional predictive features were extracted:

- Month
- Day

Logarithmic Returns (Log Returns) were also computed for each financial variable to improve model learning.

### Model Comparison

The predictive performance of all models was compared before and after feature engineering.

Finally, the best-performing model was used to generate next-day predictions, which were compared against the actual closing prices.

---

## Technologies

- Python
- Pandas
- NumPy
- Plotly
- Scikit-learn
- yfinance
- Google Colab

---

## Machine Learning Techniques

- Time Series Forecasting
- Sliding Window Representation
- Ensemble Learning
- Random Forest
- Bagging
- Stacking
- Feature Engineering
- Log Returns

---

## Evaluation Metric

The models were evaluated using:

- Mean Absolute Error (MAE)

---

## Repository Structure

```
├── Assignment3_Ensemble_Models.ipynb
├── README.md
```

---

## Author

Georgia Takatzoglou

M.Sc. Data and Web Science  
Physics Graduate | Machine Learning | Data Science
