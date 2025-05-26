# 📈 Lokesh Machines Stock Price Prediction using LSTM

This project uses a Long Short-Term Memory (LSTM) neural network to predict the future stock prices of Lokesh Machines (`LOKESHMACH.NS`) based on historical time series data.

---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- TensorFlow / Keras (LSTM model)
- yFinance API (Data)
- Pandas, NumPy, Matplotlib
- Technical Indicators (Moving Average, RSI)

---

## 📊 Features

- Fetch historical stock data using `yfinance`
- Normalize and sequence data for LSTM input
- Train multivariate LSTM on 5 features: Open, High, Low, Close, Volume
- Predict and plot stock prices
- Visualize 50-day Moving Average and RSI indicators
