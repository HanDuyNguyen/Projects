# Predicting  Stock Movements using Machine Learning

In this notebook, we are going to go through a machine learning project with the goal of predicting the stock movement of an unknown asset.

## 1. Problem definition

> How well can we  predict stock movement based on real-market orderbook data ?

## 2. Data

The full dataset <code>data-training.csv</code>  is provided by the XTX Market company. The data consist 31 columns and 2999999 rows. The total size of the data is 1 GB which is quite large.

## 3. Evaluation

The evaluation metric for this problem is the Coefficient of determination (r2 score). For more information about the r2 score check: https://en.wikipedia.org/wiki/Coefficient_of_determination.

## 4. Features

The data features can be grouped into four groups: askRate, askSize, bitRate, bitSize. Each group has 14 features, for example askRate1,...,askRate14. 

# Instructions

* <code>XTX_EDA.ipynb</code> contains the codes for Exploratory Data Analysis.
  
* <code>XTX_LSTM.ipynb</code> contains the Long-Short-Term memory model.
  
* <code>XTX_XGBoost.ipynb</code> contains the XGBoost model which give the lowest test error.  

