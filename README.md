# Tesla (TSLA) Stock Price Prediction: RNN vs LSTM Comparison

A professional Deep Learning project that compares the performance of **Simple Recurrent Neural Networks (RNN)** and **Long Short-Term Memory (LSTM)** networks in forecasting stock market prices.

## 📌 Project Overview
Predicting stock prices is a complex time-series task. This project fetches real-time data for Tesla (TSLA) and builds two different architectures to see which one handles long-term dependencies better.

### Why not use "Accuracy"?
In this regression task (predicting continuous values), standard "Accuracy" metrics used in classification are not applicable. Instead, we use:
- **MSE (Mean Squared Error):** To measure the average squared difference between estimated and actual values.
- **MAE (Mean Absolute Error):** To measure the average magnitude of errors in the predictions (closer to 0 is better).

## 🚀 Features
- **Live Data Fetching:** Automatically downloads the latest TSLA data using `yfinance`.
- **Pre-processing:** Automated data scaling using `MinMaxScaler` and sliding window sequence generation.
- **Model Comparison:** Direct performance comparison between Simple RNN and LSTM.
- **Visualization:** Generates a professional comparison chart saved as `RNN_vs_LSTM_Comparison.png`.

## 🛠 Installation & Usage
1. Clone this repository:
   ```bash
   git clone [https://github.com/your-username/Tesla-Stock-Prediction.git](https://github.com/your-username/Tesla-Stock-Prediction.git)
