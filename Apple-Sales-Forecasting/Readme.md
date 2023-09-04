
### Model 1 (ARIMA)

Model 1 is based on the ARIMA algorithm for stock price forecasting.

**Overview**
- **Objective:** To predict the closing stock prices within a specified date range.
- **Algorithm Used:** ARIMA (AutoRegressive Integrated Moving Average).
- **Language:** Python.
- **Libraries:** pandas, numpy, matplotlib, yfinance.

**Usage**
1. Install the required libraries if not already installed: `pip install pandas numpy matplotlib yfinance`.
2. Modify the `stock_symbol`, `start_date`, `end_date`, and `order` in the script as per your requirements.
3. Run the script: `python ARIMA_METHOD.py`.

**Results**
- The Root Mean Squared Error (RMSE) for the forecasted stock prices: 17.85.

### Model 2 (LSTM)

Model 2 uses Long Short-Term Memory (LSTM) networks for stock price prediction.

**Overview**
- **Objective:** To predict the closing stock prices within a specified date range.
- **Algorithm Used:** LSTM.
- **Language:** Python.
- **Libraries:** pandas, numpy, matplotlib, yfinance, scikit-learn, tensorflow, tsfresh.

**Usage**
1. Install the required libraries if not already installed: `pip install pandas numpy matplotlib yfinance scikit-learn tensorflow tsfresh`.
2. Modify the `stock_symbol`, `start_date`, and `end_date` in the script as per your requirements.
3. Apply Feature extraction, Feature selection, and Windowing as preprocessing steps.
4. Run the script: `python LSTM_Using_Feature_Extraction_Selection.py`.

**Results**
- The Root Mean Squared Error (RMSE) for the forecasted stock prices: 3.96.

### Model 3 (XGBoost)

Model 3 employs the XGBoost algorithm for stock price forecasting.

**Overview**
- **Objective:** To predict closing stock prices using the XGBoost algorithm, a gradient boosting technique.
- **Algorithm Used:** XGBoost.
- **Language:** Python.
- **Libraries:** pandas, numpy, matplotlib, yfinance, scikit-learn, xgboost.

**Usage**
1. Install the required libraries if not already installed: `pip install pandas numpy matplotlib yfinance scikit-learn xgboost`.
2. Modify the `stock_symbol`, `start_date`, and `end_date` in the script as per your requirements.
3. Run the script: `python XGBOOST_METHOD.py`.

**Results**
- The Root Mean Squared Error (RMSE) for the forecasted stock prices: 14.34.

### Model 4 (Prophet)

Model 4 uses the Prophet library for stock price prediction.

**Overview**
- **Objective:** To predict closing stock prices using the Prophet library, developed by Facebook.
- **Algorithm Used:** Prophet.
- **Language:** Python.
- **Libraries:** pandas, numpy, matplotlib, yfinance, fbprophet.

**Usage**
1. Install the required libraries if not already installed: `pip install pandas numpy matplotlib yfinance fbprophet`.
2. Modify the `stock_symbol`, `start_date`, and `end_date` in the script as per your requirements.
3. Run the script: `python model4.py`.

**Results**
- The Root Mean Squared Error (RMSE) for the forecast 23,09
