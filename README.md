# AI for Market Trend Analysis 📈

## 📌 Project Overview
An end-to-end AI system designed to analyze financial time-series data, detect market trends,
and forecast future stock prices using both statistical (Prophet) and Deep Learning (LSTM)
methodologies.

## 🎯 Objectives
* Perform Exploratory Data Analysis (EDA) on historical market data.
* Detect Bullish/Bearish market regimes.
* Compare traditional forecasting (Prophet) vs. Neural Networks (LSTM).
* Generate actionable insights for financial decision-making.

## 🛠️ Tech Stack
* **Language**: Python 3.8+
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **ML/DL**: Facebook Prophet, TensorFlow/Keras (LSTM)
* **Environment**: Virtual Environment / Conda (Jupyter Notebook based)

## 📊 Models Implemented
1. **Prophet**  
   Used as a baseline statistical model to capture long-term trends and seasonality.

2. **LSTM (Long Short-Term Memory)**  
   A deep learning recurrent neural network capable of learning complex, non-linear
   temporal dependencies in financial time-series data.

## 🚀 How to Run
1. (Optional but recommended) Create and activate a virtual environment:
   ```bash
   python -m venv market_env
   source market_env/bin/activate   # macOS/Linux
   market_env\Scripts\activate      # Windows
