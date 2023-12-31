# EDA StockData

This repository documents the process of performing data cleaning, exploratory data analysis (EDA), and basic model training on stock market data. The primary objective is to demonstrate how to prepare and analyze stock data, gain insights from exploratory analysis, and create a simple machine learning model for prediction.

## Dataset

The dataset used in this project contains historical stock market data for (https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data). It includes features such as date, open price, high price, low price, close price, trading volume, and more.

## Data Cleaning

Data cleaning is a crucial step in the data analysis process. In this project, we performed the following data cleaning tasks:

- Handling missing data: We addressed missing values by imputing or removing them, depending on the nature of the data and the impact of missing values on the analysis.

- Data format conversion: We ensured that date columns were in the correct datetime format for time series analysis.

- Removing duplicates: We removed duplicate entries, if any, to maintain data integrity.

## Exploratory Data Analysis (EDA)

EDA is essential for understanding the characteristics and patterns in the data. Here are some of the key EDA tasks performed:

- Data visualization: We created various visualizations, including line plots, bar charts, and candlestick charts, to explore stock price trends, volume, and volatility.

- Summary statistics: We computed summary statistics to gain insights into the central tendencies and distributions of the data.

- Correlation analysis: We examined correlations between stock prices and other relevant variables to identify potential relationships.

## Basic Model Training

As part of this project, we built a basic machine learning model for stock price prediction. The following steps were taken:

- Feature selection: We selected relevant features for the model, considering factors that could influence stock prices.

- Data splitting: We divided the dataset into training and testing sets to train and evaluate the model's performance.

- Model selection: We chose a simple regression model, such as linear regression or time series forecasting techniques, for stock price prediction.

- Model training: We trained the selected model on the training data.

- Model evaluation: We assessed the model's performance using appropriate evaluation metrics, such as Mean Absolute Error (MAE) or Root Mean Square Error (RMSE).
