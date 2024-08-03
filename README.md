# California Housing Price Prediction

This project uses the California Housing dataset to predict housing prices using three different regression models: Linear Regression, Decision Tree Regressor, and Random Forest Regressor. The models are compared based on their performance metrics.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Performance Metrics](#performance-metrics)
- [Results](#results)
- [Usage](#usage)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction

The aim of this project is to build and compare different regression models to predict housing prices in California. The models compared are:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Dataset

The dataset used in this project is the California Housing dataset, which contains information about various features of houses in California and their corresponding prices. The dataset can be found [here](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html).

## Models

1. **Linear Regression**
   - A simple linear approach to model the relationship between the target variable and the independent variables.

2. **Decision Tree Regressor**
   - A non-linear model that splits the data into subsets based on feature values and makes predictions based on the mean value of the target variable in each subset.

3. **Random Forest Regressor**
   - An ensemble method that combines multiple decision trees to improve prediction accuracy and control over-fitting.

## Performance Metrics

The models are evaluated based on the following metrics:
- Mean Squared Error (MSE)
- R-squared (R²) score

## Results

The results of the model comparisons are as follows:

| Model                  | RMSE          | R² Score     |
|------------------------|---------------|--------------|
| Linear Regression      | 0.02951812    | 0.4822705    |
| Decision Tree Regressor| 0.04787512    | 0.1603004    |
| Random Forest Regressor| 0.03842823    | 0.3259969    |

## Usage

To run the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Mobeen0/housing_prices_regression
