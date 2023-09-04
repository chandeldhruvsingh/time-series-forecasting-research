# IoT Sensor Data Analysis

## Introduction

This README file provides an overview and usage instructions for four different models used to analyze IoT sensor data. Each model serves a unique purpose and employs specific algorithms and libraries to process and make predictions based on sensor data.

## Model 1 (LSTM)

**Overview**

- **Objective**: To predict the future temperature readings.
- **Algorithm Used**: LSTM (Long Short-Term Memory) networks.
- **Language**: Python.
- **Libraries**: pandas, numpy, matplotlib, scikit-learn, tensorflow, tsfresh.

**Usage**

1. Install the required libraries if not already installed: `pip install pandas numpy matplotlib scikit-learn tensorflow tsfresh`.
2. Resample the data by one-minute intervals because it is scattered.
3. Apply Feature extraction, Feature selection, and Windowing as preprocessing steps.
4. Run the script: `python LSTM_sensor.py`.

**Results**

- The Root Mean Squared Error (RMSE) for the acutal temp readings and forecasted temp readings: 0.1138.

## Model 2 (XGBoost)

**Overview**

- **Objective**: To predict the future temperature readings with the help of gradient boosting technique.
- **Algorithm Used**: XGBoost.
- **Language**: Python.
- **Libraries**: pandas, numpy, matplotlib, scikit-learn, xgboost, LabelEncoder, hyperopt.

**Usage**

1. Install the required libraries if not already installed: `pip install pandas numpy matplotlib scikit-learn xgboost`.
2. Resample the data by one-minute intervals because it is scattered.
3. Run the script: `python XGBoost_sensor.py`.

**Results**

- The Root Mean Squared Error (RMSE) for the acutal temp readings and forecasted temp readings: 2.8591.

## Model 3 (Prophet)

**Overview**

- **Objective**: To predict the future temperature readings with the help of prophet developed by Facebook.
- **Algorithm Used**: Prophet.
- **Language**: Python.
- **Libraries**: pandas, numpy, matplotlib, prophet.

**Usage**

1. Install the required libraries if not already installed: `pip install pandas numpy matplotlib prophet`.
2. Resample the data by one-minute intervals because it is scattered.
3. Run the script: `python Prophet_sensor.py`.

**Results**

- The Root Mean Squared Error (RMSE) for the acutal temp readings and forecasted temp readings: 0.5824.

## Model 4 (ARIMA)

**Overview**

- **Objective**: To predict the future temperature readings with the help of moving average.
- **Algorithm Used**: ARIMA (AutoRegressive Integrated Moving Average).
- **Language**: Python.
- **Libraries**: pandas, numpy, matplotlib, ARIMA.

**Usage**

1. Install the required libraries if not already installed: `pip install pandas numpy matplotlib ARIMA`.
2. Resample the data by one-minute intervals because it is scattered.
3. Run the script: `python ARIMA_sensor.py`.

**Results**

- The Root Mean Squared Error (RMSE) for the acutal temp readings and forecasted temp readings: 1.1409.



