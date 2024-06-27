# Stock Price Predictor 2.0

This repository hosts a stock price predictor model version 2.0, which predicts stock prices for various companies using linear regression.

## Overview

The model utilizes linear regression from scikit-learn and includes preprocessing techniques such as MinMaxScaler and LabelEncoder.

## Dataset

The dataset contains historical stock prices for the following companies:

- Apple Inc.
- Adobe Inc.
- Amazon.com, Inc.
- Salesforce, Inc.
- Cisco Systems, Inc.
- Alphabet Inc.
- International Business Machines Corporation
- Intel Corporation
- Meta Platforms, Inc.
- Microsoft Corporation
- Netflix, Inc.
- NVIDIA Corporation
- Oracle Corporation
- Tesla, Inc.

## Performance Metrics

The model's performance on a test set is as follows:

- **Mean Squared Error (MSE):** 2.838900674489199e-06
- **Root Mean Squared Error (RMSE):** 0.0016849037582275135
- **R-squared (R2):** 0.9998737573519603
- **Mean Absolute Error (MAE):** 0.0007451391779980222

## Techniques Used

- **Linear Regression:** Used as the predictive model.
- **MinMaxScaler:** Applied to normalize numerical features.
- **LabelEncoder:** Used to encode categorical variables (stock symbols).


## Requirements

- Python 3.x
- NumPy
- Pandas
- Scikit-learn

