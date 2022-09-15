# Stock Price Predictor
This project seeks to predict future Stock values by using Deep Learning models.

# Overview:
Stock market play a very vital role in driving today's world economy. While it is extremely valuable for investors to know the exact future values of a stock, it is extremely hard to predict the stock prices correctly. In this project I have used Long-Short Term Memory (LSTM) Neural Network algorithm to solve the problem of Stock Prices Prediction by utilizing this Deep Learning model to predict future stock values.  This project uses historical data of the stock values of 'Microsoft Corporation' that have been acquired from the public datasets of Quandl.

# Technical Overview:
The data that we deal with in this project is a time-series. In order to make predictions on this time-series data we use convert it to features and labels by using the sliding window technique. Then I trained a model with 3 LSTM layers and a dense layer to predict the stock prices of the next 30 days. Since this is a regression task, I used RMSE as a metric of model performance.

# Results:
Predictions on training and test data

![train-test-predictions](https://github.com/r-mohanty/Stock-Price-Predictor/blob/main/train-test-predictions.png)

Prediction results for the last 30 days

![30-day](https://github.com/r-mohanty/Stock-Price-Predictor/blob/main/30-day-plot.png)

Final Series with the predicted stock prices

![final-pred](https://github.com/r-mohanty/Stock-Price-Predictor/blob/main/Final-series.png)