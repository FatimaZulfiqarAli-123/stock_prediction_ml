#  Stock Price Prediction & Algorithmic Trading Strategy

---

##  Project Overview
This project uses **Machine Learning and Deep Learning models** to predict next-day stock prices using historical market data. It also evaluates a trading strategy based on predicted price movements and compares multiple models using financial performance metrics.

---
<p align="center">
  <a href="https://www.python.org/" target="_blank">
    <img src="https://img.shields.io/badge/Python-ML-blue?style=flat-square">
  </a>

  <a href="https://www.tensorflow.org/" target="_blank">
    <img src="https://img.shields.io/badge/Deep%20Learning-LSTM%20%7C%20GRU-orange?style=flat-square">
  </a>

  <a href="https://en.wikipedia.org/wiki/Stock_market" target="_blank">
    <img src="https://img.shields.io/badge/Finance%20Project-Stock%20Prediction-green?style=flat-square">
  </a>
</p>

## 📄 Manuscript

You can view the full detailed project manuscript here:

👉 **[Comparative Analysis of 
Machine Learning and 
Deep Learning Models 
for Apple (AAPL) Stock 
Price Prediction ](https://drive.google.com/file/d/1kp_Q3CWS-Up-vz5fi-s0SWhcTT0gzhf8/view?usp=drive_link)**

---

## ⚙️ Workflow
Data Collection → Feature Engineering → Model Training → Prediction → Backtesting → Performance Evaluation

---

## 📊 Dataset

- Source: Yahoo Finance (`yfinance`)
- Stock: Apple Inc. (AAPL)
- Time Period: 2020 - 2024

### Features:
- Open, High, Low, Close, Volume
- Lag Features (Close_lag1, Close_lag2)
- Moving Averages (MA5, MA10)

---

## 🧠 Models Used

### Machine Learning Models
- Linear Regression → Baseline statistical model
- Random Forest → Captures non-linear relationships

### Deep Learning Models
- LSTM → Learns long-term time dependencies
- GRU → Efficient recurrent neural network variant

---

## 📉 Trading Strategy

- If Predicted Price > Previous Close → BUY (1)
- Else → SELL (-1)

The strategy is evaluated using:
- Returns
- Sharpe Ratio
- Maximum Drawdown

---

## 📊 Results Summary

| Model              | Description                     | Performance |
|-------------------|----------------------------------|-------------|
| Linear Regression | Simple baseline model            | Medium      |
| Random Forest     | Non-linear ML model              | Good        |
| LSTM              | Deep sequence learning model     | Best DL     |
| GRU               | Faster recurrent model           | Competitive |

---

## 📈 Evaluation Metrics

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score
- Total Strategy Return
- Sharpe Ratio
- Maximum Drawdown

---

## 📦 Installation

```bash
pip install -r requirements.txt
