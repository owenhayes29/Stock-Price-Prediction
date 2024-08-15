# Stock Price Prediction using Machine Learning

## Overview
Predicting the stock market is one of the most critical applications of Machine Learning in finance. This project demonstrates a simple Data Science approach to predict stock prices using the Python programming language and a Linear Regression model. By the end of this project, you will learn how to predict stock prices using historical data and the Linear Regression model.

## Project Description
The stock market is a dynamic environment where billions of dollars are traded daily, with investors seeking to profit from market fluctuations. Accurate stock price prediction offers the potential for significant financial gain and influence. This project leverages Machine Learning to predict stock prices, providing a valuable tool for traders and investors.

### Key Steps:
1. **Data Preparation**:
   - **Import Libraries**: Import necessary Python libraries such as `numpy`, `pandas`, `sklearn`.
   - **Prepare Data**: Write a function to prepare the dataset for the Linear Regression model. This includes creating features, scaling the data, and splitting it into training and testing sets.

2. **Reading the Data**:
   - Load the dataset containing stock prices.
   - Filter the dataset to focus on the stock symbol of interest (e.g., "GOOG").

3. **Declaring Input Variables**:
   - Define the column to predict (e.g., `close` price).
   - Set how far into the future you want to make predictions (e.g., 5 days).
   - Determine the size of the test set for cross-validation.

4. **Applying Machine Learning**:
   - Split the data into training and testing sets.
   - Initialize and train a Linear Regression model on the training data.
   - Predict future stock prices using the trained model and evaluate its performance.# Stock-Price-Prediction
