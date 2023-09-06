Overview

The below directory contains three different models for forecasting Walmart sales data, in these three different models, we have used different algorithms and libraries to forecast the future sales of stores of Walmart.

Model 1 (Prophet)
Model 1 is based on the Prophet algorithm for Walmart sales data forecasting.

Overview

Objective: The main objective of this model is to forecast the monthly sales of Walmart stores
Algorithm Used: Prophet
Language: Python.
Libraries: pandas, numpy, matplotlib, prophet.


Usage
Install the required libraries if not already installed: pip install pandas numpy matplotlib prophet.
Modify the features as per your requirements.
Run the script: python Prophet_algorithm.ipynb.

Results
The Root Mean Squared Error (RMSE) for the forecasted sales: 1087.55


Model 2 (SARIMA)
This model is used to predict the future monthly sales of Walmart stores 
Overview

Objective: The main objective of this model is to forecast the monthly sales of Walmart stores
Algorithm Used: Seasonal AutoRegressive Integrated Moving Average (SARIMA).
Language: Python.
Libraries: pandas, numpy, matplotlib,statsmodels.

Usage

Install the required libraries if not already installed: pip install pandas numpy matplotlib statsmodels
Modify the data source, preprocessing steps, and SARIMA model parameters as per your specific Walmart sales data.
Run the script: python SARIMA_algorithm.ipynb.
Results
The Root Mean Squared Error (RMSE) for the forecasted sales: 6897.78


Model 3 ( XGBoost)
Overview

Objective: The main objective of this model is to forecast the monthly sales of Walmart stores
Algorithm Used: XGBoost.
Language: Python.
Libraries: pandas, numpy, matplotlib, scikit-learn, xgboost.

Usage

Install the required libraries if not already installed: pip install pandas numpy matplotlib scikit-learn, xgboost.
Modify the preprocessing steps, and XGBoost model parameters as per your specific requirements.
Run the script: python XGBoost.ipynb.

Results
The Root Mean Squared Error (RMSE) for the forecasted sales: 7005.51

