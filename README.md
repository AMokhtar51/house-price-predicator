# House Price Predictor
A linear regression model built from scratch using only NumPy, trained on a real housing dataset

## Overview
This project implements linear regression with gradient descent from scratch, no scikit-learn or ML Libraries. My goal was to understand core concepts of the algorithm like MSE cost function, gradient descent from scratch and in the end a comparsion with scikit-learn to evaluate my model accuracy,

## Features
- Feature Encoding - One-Hot Encoding, Binary Encoding
- Feature Scaling - Normalization Z-score
- Linear Regression - Supervised ML algorithm 
- MSE cost function - Mean squared error
- Gradient descent - parameters updates over 5000 epochs
- Visualization - scatter plot per feature vs price and training loss curve
- scikit-learn - uses model.fit() for linear regression to compare results

# Dataset
[Housing Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset) - 545 samples, 12 features including area, bedrooms, bathrooms and more.

## Dependencies
```
pip install numpy matplotlib pandas scikit-learn
```
