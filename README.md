# AI for Market Trend Analysis 📈

## 📌 Project Overview
An end-to-end AI system designed to analyze financial time-series data, detect market trends, and forecast future stock prices using both statistical (Prophet) and Deep Learning (LSTM) methodologies.

## 🎯 Objectives
* Perform Exploratory Data Analysis (EDA) on historical market data.
* Detect Bullish/Bearish market regimes.
* Compare traditional forecasting (Prophet) vs. Neural Networks (LSTM).
* Generate actionable insights for financial decision-making.

## 🛠️ Tech Stack
* **Language**: Python 3.8+
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **ML/DL**: Facebook Prophet, TensorFlow/Keras (LSTM)

## 📊 Models Implemented
1.  **Prophet**: Used as a baseline for capturing seasonality and trend components.
2.  **LSTM (Long Short-Term Memory)**: A Recurrent Neural Network (RNN) optimized for sequence prediction and complex pattern recognition.

## 🚀 How to Run
1.  Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn prophet tensorflow`
2.  Place `Market_Trend_Analysis.csv` in the root directory.
3.  Run the script: `python main.py`
4.  View generated plots (`eda_*.png`, `forecast_*.png`) and console metrics.

## 📉 Results Summary
* **Trend Detection**: Successfully identified market regime shifts using SMA/RSI.
* **Forecasting**: LSTM outperformed Prophet with a lower RMSE, demonstrating superior handling of volatility.

## ⚠️ Disclaimer
This project is for **academic purposes only** (IIT Ropar Minor in AI). It does not constitute financial advice.
