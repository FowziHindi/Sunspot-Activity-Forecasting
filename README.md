# Sunspot Activity Forecasting
An AI-driven approach to forecasting solar activity cycles using Linear Autoregressive (AR) models.

## Project Overview
This project focuses on predicting solar activity cycles by building an elementary neural network structure. It compares different optimization techniques to model the k-th value of a time series based on historical data from 1700 to 2014.

## Tech Stack
* **Language:** Python
* **Libraries:** Scikit-learn, NumPy, Matplotlib, Seaborn

## Key Features
* **Data Engineering:** Implemented a sliding-window pipeline to transform raw time-series data into high-dimensional input matrices.
* **Optimization Comparison:** Evaluated **Ordinary Least Squares (OLS)** versus **Stochastic Gradient Descent (SGD)** using Mean Squared Error (MSE).
* **Visualization:** Generated 3D regression planes to interpret model weights, bias, and convergence patterns.
EOF
