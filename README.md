Google Stock Price Prediction using Linear Regression

This project uses Python, yfinance, and scikit-learn to fetch historical stock data for Google (GOOGL) and predict its future prices using Linear Regression.

Features
- Real-time data download using `yfinance`
- Preprocessing and feature engineering with Pandas
- Model training and prediction using `scikit-learn`
- Visualization with `matplotlib`
- Saves stock data as a CSV file

Libraries Used
- `yfinance`
- `pandas`
- `matplotlib`
- `scikit-learn`

How It Works
1. Downloads GOOGL historical stock data from 2020 to 2024
2. Creates a new column to shift the target values 30 days ahead
3. Splits the data into training and testing sets
4. Trains a Linear Regression model
5. Predicts the next 30 days of stock prices
6. Displays the predictions on a line graph

Output
- A plot showing predicted stock prices for the next 30 days
- Saved CSV file of historical GOOGL stock data
