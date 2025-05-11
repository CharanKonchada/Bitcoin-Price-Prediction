
🚀 Bitcoin Price Prediction using Traditional time series and LSTM! 📈💡

This project uses a deep learning approach—specifically Long Short-Term Memory (LSTM) networks—to forecast Bitcoin closing prices using historical market data. It focuses on capturing temporal trends in Bitcoin prices for accurate time series prediction.

---

## 🔍 Dataset

* **Source**: [Kaggle – Bitcoin Historical Data](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data)
* **Features Used**: `Open`, `High`, `Low`, `Close`, `Volume`
* **Frequency**: Converted to daily granularity
* **Preprocessing**: Missing values removed, data normalized using `MinMaxScaler`

---

## 🧠 Model Overview

* Architecture: Multi-layer LSTM with dropout regularization
* Target: Predicting the next day's **closing price**
* Customizable sequence window (`SEQ_LEN`)
* Evaluation Metrics:

  * **Mean Absolute Error (MAE)**: `1,930.36`
  * **Root Mean Squared Error (RMSE)**: `2,589.94`
  * **R² Score (Accuracy)**: `98.88%`

---

## 🔧 Features

* Flexible sequence length for experimentation
* Clean, scalable model architecture
* Side-by-side plot of actual vs. predicted prices
* Strong performance on daily time series data

---

## 🧰 Libraries Used

* `NumPy`, `Pandas`
* `Matplotlib`, `Seaborn`
* `TensorFlow / Keras`
* `scikit-learn`
* `statsmodels / acf, pacf api`

---

## 📊 Results

> **MAE**: 1,930.36

> **RMSE**: 2,589.94

> **Accuracy (R²)**: 98.88%

---

## ⚠️ Disclaimer

> **This project is for educational and research purposes only.**

> While the model shows high accuracy (\~98.88%), it should **not** be used for actual financial trading or investment decisions. Cryptocurrency markets are highly volatile, and even the most accurate models can fail under real-world conditions.

> **Use at your own risk. Do not invest based solely on this prediction model.**



