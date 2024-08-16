# Stock Price Prediction using LSTM

This project implements a stock price prediction model using Long Short-Term Memory (LSTM) neural networks. It focuses on predicting the opening price of State Bank of India (SBI) stock based on historical data.

## Project Overview

The project uses historical stock data from SBI (SBIN.NS) to predict future stock prices. It employs a stacked LSTM model with dropout layers for improved generalization.

Key features:
- Data preprocessing and normalization
- Time series data preparation for LSTM input
- Implementation of a stacked LSTM model
- Model training and evaluation
- Visualization of predictions

## Dataset

The dataset used is "SBIN.NS.csv", which contains historical stock data for SBI including Date, Open, High, Low, Close, Adjusted Close, and Volume.

## Model Architecture

The model consists of:
- 3 LSTM layers (50 units each) with L2 regularization
- 2 Dropout layers (50% dropout rate)
- 1 Dense output layer

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- TensorFlow
- Scikit-learn

## Usage

1. Ensure all required libraries are installed.
2. Place the "SBIN.NS.csv" file in the appropriate directory.
3. Run the script to train the model and generate predictions.

## Results

The model is evaluated using Root Mean Square Error (RMSE) on both training and test data. The predictions are visualized against actual stock prices.

## Future Work

- Experiment with different model architectures
- Incorporate additional features for prediction
- Implement real-time prediction capabilities
