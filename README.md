# ATM Cash Demand Forecasting

## Overview [![Report](https://img.shields.io/badge/Report-blue?style=flat)](https://github.com/seoyeon3/Econ3203/blob/main/Report.pdf) [![Code](https://img.shields.io/badge/Code-grey?style=flat)](https://github.com/seoyeon3/Econ3203/blob/main/data_analysis.ipynb)
Developed predictive models to forecast ATM cash demand, enabling more efficient cash management and operational planning for banking systems.

## Problem
Accurate prediction of ATM withdrawals is critical for ensuring sufficient cash availability while minimizing operational costs.

## Approach
- Performed exploratory data analysis and feature engineering (interaction terms, standardisation)  
- Built and compared multiple regression models:
  - Multiple Linear Regression  
  - Lasso, Ridge, Elastic Net  
  - K-Nearest Neighbours (KNN)  
- Applied cross-validation and model selection based on mean squared error (MSE)  

## Results
- Best Model: K-Nearest Neighbours (KNN)  
- Test MSE: **0.3156**  
- Outperformed linear and regularised regression models  

