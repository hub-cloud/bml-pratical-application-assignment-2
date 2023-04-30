# Vehicle Price Prediction

This repository contains the code and analysis for predicting vehicle prices based on various features. We have used three different models (Linear Regression, Ridge Regression, and Lasso Regression) to understand the importance of each feature in determining the price of a vehicle.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Analysis](#analysis)
  - [Linear Regression](#linear-regression)
  - [Ridge Regression](#ridge-regression)
  - [Lasso Regression](#lasso-regression)
- [Conclusion](#conclusion)

## Introduction

The purpose of this project is to determine the key factors that influence the price of a vehicle. Understanding these factors can help potential buyers make more informed decisions when purchasing a vehicle and assist sellers in setting appropriate prices for their vehicles.

## Data

The dataset used in this analysis contains information about various vehicles, including their features and prices. The features include:

- Odometer reading
- Drive type
- Number of cylinders
- Fuel type
- Title status
- Condition
- Vehicle type
- Paint color
- Manufacturer

## Analysis

We have performed an analysis using three different models: Linear Regression, Ridge Regression, and Lasso Regression. The results highlight the importance of each feature in determining the price of a vehicle.

### Linear Regression

The Linear Regression model helps us understand the relationship between the features and the price. The results indicate the significance of each feature in predicting the price.

### Ridge Regression

Ridge Regression is a variation of Linear Regression that incorporates L2 regularization. This model helps in preventing overfitting and improving the model's generalization.

### Lasso Regression

Lasso Regression is another variation of Linear Regression that includes L1 regularization. This model can shrink some coefficients to zero, effectively performing feature selection.

## Conclusion

Our analysis shows that the odometer reading, drive type, and the number of cylinders are the main factors that influence a vehicle's price. The consistency of these top features across different models underscores their importance in the price prediction process.

To access the Jupyter Notebook file and the data file, please use the following links:

- [Notebook File](./solution.ipynb)
- [Data File](./data/vehicles.csv) (file has to be unzipped to be used)
