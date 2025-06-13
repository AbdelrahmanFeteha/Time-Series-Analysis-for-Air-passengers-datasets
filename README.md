# Time Series Forecasting with Neural Networks

This notebook was created as part of the **Neural Networks Summer Certification Program** at the **American University of Sharjah (AUS)**. The 2-day workshop was led by **Ms. Maram Helmy**, who guided us step-by-step through this project. All code presented here was written as instructed during the sessions.

## Project Summary

We applied time series forecasting techniques to the well-known **International Airline Passengers** dataset to predict future values. The analysis covers both classical time-series decomposition and modern deep learning methods.

## Key Features

- **Data Preparation:** Time-indexing, trend and seasonality decomposition, stationarity tests (ADF), autocorrelation analysis.
- **Forecasting Models:**
  - Feedforward Neural Network (FNN)
  - Long Short-Term Memory (LSTM)
  - Stacked LSTM and ConvLSTM architectures
- **Evaluation Metrics:** RMSE on training and testing datasets.
- **Visualization:** Comparison plots for original vs. predicted sequences.

## Dataset

- Source: [Kaggle - Air Passengers Dataset](https://www.kaggle.com/rakannimer/air-passengers)
- Contains monthly international airline passenger numbers from 1949 to 1960.

## Usage

To run this notebook:
1. Install required libraries: `keras`, `scikit-learn`, `pandas`, `matplotlib`, `seaborn`, and `statsmodels`.
2. Load the dataset (`AirPassengers.csv`) into your working directory.
3. Run each cell in sequence to reproduce the results and visualizations.

## Acknowledgment

This project was completed as part of the Neural Networks Summer Certification Program held at the American University of Sharjah (AUS). The program was an intensive 2-day workshop, and the code in this notebook was written and explained live by Ms. Maram Helmy, who guided us through each step. The implementation follows exactly what she demonstrated during the sessions.
