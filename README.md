# Stock Price Prediction using ARIMA and LSTM

## Overview
This repository contains a Python notebook that predicts the **closing price of a stock (CEATLTD)** using two different time-series forecasting approaches:
- **ARIMA (AutoRegressive Integrated Moving Average)**
- **Univariate LSTM (Long Short-Term Memory) Neural Network**

The goal of this project is to compare a **traditional statistical model** with a **deep learning-based model** for stock price forecasting.

## Dataset
- Historical stock price data of **CEATLTD**
- Target variable: **Close Price**

## Models Used
### ARIMA
- Requires stationarity
- Uses differencing, ACF, and PACF for parameter selection
- Captures linear temporal dependencies

### LSTM
- Sequence-based deep learning model
- Uses sliding window technique
- Data normalized using Min-Max Scaling

## Results & Observations
- ARIMA performs well on short-term linear trends
- But for a long term ARIMA fails as it accumulates error over time.
- LSTM captures complex, non-linear patterns better
- Model predictions and residuals are visualized for comparison

## Files
- `notebook.ipynb` – Complete implementation of ARIMA and LSTM models, preprocessing, training, and evaluation


## Conclusion
This project highlights the strengths and limitations of both statistical and deep learning approaches for time-series forecasting.
