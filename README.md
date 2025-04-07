Bitcoin Price Prediction Using Machine Learning
Project Overview
This project focuses on predicting future prices of Bitcoin (BTC) using historical data and machine learning models. The goal is to analyze Bitcoin price trends and build predictive models to estimate its closing price. This project can be valuable for data-driven crypto trading strategies or investment analysis.

 Dataset
Source: Kaggle - Bitcoin Historical Data

Contents: Daily Bitcoin price data with the following columns:

Date

Open, High, Low, Close

Volume, Market Cap

 Tech Stack
Python

Pandas, NumPy for data manipulation

Matplotlib, Seaborn for data visualization

Scikit-learn for ML models

XGBoost, Linear Regression, Random Forest

(Optional: LSTM using TensorFlow/Keras for time series deep learning)

 EDA Highlights
Handled missing values and formatted date/time

Visualized:

Bitcoin closing price trend over time

Correlation heatmap of all numerical features

Rolling averages (7-day, 30-day) for trend smoothing

Feature Engineering:

Created lag features (previous day's prices)

Added rolling statistics (mean, std)

Used Date to extract Day, Month, Year

 Model Training
Problem Type: Time Series Regression

Target Variable: Close price

Models tested:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Evaluation Metrics:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score
