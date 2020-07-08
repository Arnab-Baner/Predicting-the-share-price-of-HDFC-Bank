# Predicting-the-share-price-of-HDFC-Bank

## Project Goal

The goal of the project is to forecast the closing share prices of HDFC bank using Recurrent Neural Networks

## About the dataset

The dataset has been collected from Money Control. The timeframe for the dataset has been 1229 days ranging from 30th June 2015 to 29th June 2020. The dataset contains multiple variables like date, open, high, low, last, close, total trade quantity, and turnover. The analysis in the project has been restricted to the closing share prices. The market is closed on weekends and public holidays which is depicted in the missing days in the dataset.

## Models Used

Here Recurrent Neural Network has been used to predict the closing share price. The moving average model has also been used as a reference model to understand the efficiency of the Recurrent Neural Network in prediction. The Recurrent Neural Network had a root mean squared error of 162 while that for the moving average model was 40. So, the root mean squared error was reduced by 75%.
