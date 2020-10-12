# [Stock_Price_Predictions_Using_regression & LSTM](https://github.com/parthshah28/Stock_Price_Predictions_Using_regression)

## Overview:
I trained a ridge regression model to predict future stock prices. By accurately predicting stock prices, investors can maximize returns and know when to buy/sell securities.The model is trained using historical stock price data along with the volume of transcations.

### Stocks Considerd:

#### AAPL = Apple Stock 
#### BA = Boeing 
#### T = AT&T
#### MGM = MGM Resorts International (Hotel Industry)
#### AMZN = Amazon
#### IBM = IBM
#### TSLA = Tesla Motors
#### GOOG = Google 
#### sp500 = US Stock Market (S&P 500 is a stock market index that measures the stock performance of 500 large companies listed on U.S. stock exchange)

Check the list of S&P 500 companies here: https://en.wikipedia.org/wiki/List_of_S%26P_500_companies

## Data Gathering:
Historical stock price data along with the volume of transcations.

### Dataset
Train Dataset have (1402,2) columns and rows.
Test Dataset have (756,2) columns and rows.

![](https://github.com/parthshah28/Stock_Price_Predictions_Using_regression/blob/main/images/Screenshot%202020-10-09%20143241.png)

## Exploratory Data Analysis
First I defined a Function to normalize stock prices based on their initial price and then plotted interactive plots using Plotly Express.

![](https://github.com/parthshah28/Stock_Price_Predictions_Using_regression/blob/main/images/captured.gif)

## Feature Engineering

### A. Prepare the data
I defined a Function to concatenate the date, stock price, and volume in one dataframe.

### B. Feature Scaling
For scaling, MinMaxScaler has been applied.

#### to understand it in more detail go to [Stock_Price_Predictions_Using_regression](https://github.com/parthshah28/Stock_Price_Predictions_Using_regression)

## Applied Algorithm and Score:
I used Ridge Linear Regresssion(L2 Regularization).
Linear Regression Score:  0.7950028030821767

![](https://github.com/parthshah28/Stock_Price_Predictions_Using_regression/blob/main/images/captured%201.gif)

