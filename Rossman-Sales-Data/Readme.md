###  Time Series Forecasting Models for Rossman Sales Data

**Overview**                                                                                                                                                         
This directory contains code for four different time series forecasting models applied to Rossman sales data. Each model utilizes different algorithms and libraries to predict future sales data. The primary objective is to compare and evaluate the performance of these models based on Root Mean Squared Error (RMSE) values.


### Model 1 (SARIMA)
Model 1 uses SARIMA model for Rossman sales price prediction.

**Overview**
- **Objective:** To predict sales within a specified date range.
- **Algorithm Used:** Seasonal AutoRegressive Integrated Moving Average (SARIMA).
- **Language:** Python.
- **Libraries:** pandas, numpy, matplotlib, statsmodels.

**Usage**
1. Install the required libraries if not already installed: `pip install pandas numpy matplotlib statsmodels`.
2. Modify the data source, preprocessing steps, and SARIMA model parameters in the Jupyter notebook as per your specific Rossman sales data.
3. Run the script: `SARIMA_Model.ipynb`.

**Results**
- The Root Mean Squared Error (RMSE) for the forecasted sales: 85.28. 


### Model 2 (LSTM)
Model 2 uses Long Short-Term Memory (LSTM) networks for Rossman sales price prediction.

**Overview**
- **Objective:** To predict sales within a specified date range.
- **Algorithm Used:** Long Short-Term Memory (LSTM) neural networks.
- **Language:** Python.
- **Libraries:** pandas, numpy, matplotlib, scikit-learn, tensorflow.

**Usage**
1. Install the required libraries if not already installed: `pip install pandas numpy matplotlib scikit-learn tensorflow`.
2. Modify the data source, preprocessing steps, and LSTM model architecture in the Jupyter notebook according to your specific Rossman sales data.
3. Apply Feature extraction, Feature selection, and Windowing as preprocessing steps.
4. Run the script: `LSTM_Model.ipynb`.

**Results**
- The Root Mean Squared Error (RMSE) for the forecasted sales: 157.79.


### Model 3 (Prophet)
Model 3 uses the Prophet library for Rossman sales price prediction.

**Overview**
- **Objective:** To predict sales within a specified date range using the Prophet library, developed by Facebook.
- **Algorithm Used:** Prophet, a library developed by Facebook.
- **Language:** Python.
- **Libraries:** pandas, numpy, matplotlib, fbprophet.

**Usage**
1. Install the required libraries if not already installed: `pip install pandas numpy matplotlib fbprophet`.
2. Modify the data source, preprocessing steps, and Prophet model configuration in the Jupyter notebook to fit your specific Rossman sales data.
3. Run the script: `Prophet_Model.ipynb`.

**Results**
- The Root Mean Squared Error (RMSE) for the forecasted sales: 391.601.


### Model 4 (XGBoost)
Model 4 employs the XGBoost algorithm for Rossman sales price prediction.

**Overview**
- **Objective:** To predict sales within a specified date range using the XGBoost algorithm, a gradient boosting technique.
- **Algorithm Used:** XGBoost, a gradient boosting technique.
- **Language:** Python.
- **Libraries:** pandas, numpy, matplotlib, scikit-learn, xgboost.

**Usage**
1. Install the required libraries if not already installed: `pip install pandas numpy matplotlib scikit-learn xgboost`.
2. Modify the data source, preprocessing steps, and XGBoost model parameters in the Jupyter notebook based on your specific Rossman sales data.
3. Run the script: `XGBoost_Model.ipynb`.

**Results**
- The Root Mean Squared Error (RMSE) for the forecasted sales: 1354.44.





These models offer different approaches to time series forecasting, and you can choose the one that best suits your specific Rossman sales prediction needs based on the provided RMSE values and further customization.
