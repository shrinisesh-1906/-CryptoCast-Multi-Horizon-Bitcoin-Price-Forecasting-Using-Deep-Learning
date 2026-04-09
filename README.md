# 🚀 CryptoCast: Multi-Horizon Bitcoin Price Forecasting

## 📌 Overview

CryptoCast is a deep learning-based time series forecasting project designed to predict Bitcoin prices across multiple future horizons. The system leverages historical data to generate forecasts for:

* 📅 1-Day Ahead
* 📅 3-Days Ahead
* 📅 7-Days Ahead

This project demonstrates real-world applications of deep learning in financial analytics and cryptocurrency markets.

---

## 🎯 Objectives

* Learn temporal patterns from past 60 days of Bitcoin price data
* Perform multi-step forecasting using deep learning models
* Compare performance of different architectures (LSTM, CNN)
* Evaluate predictions using standard regression metrics

---

## 📊 Dataset

The dataset contains historical Bitcoin price data with the following features:

* Date
* Close Price (Target)
* Open
* High
* Low
* Volume
* Change %

---

## ⚙️ Data Preprocessing

* Converted all columns to numeric format
* Handled missing values
* Sorted data by date
* Scaled features using MinMaxScaler
* Created sequences using a sliding window (60 days)

---

## 🔁 Sequence Modeling

* Input: Past 60 days
* Output:

  * 1-Day forecast
  * 3-Day forecast
  * 7-Day forecast

---

## 🤖 Models Implemented

### 🔹 LSTM (Long Short-Term Memory)

* Captures long-term dependencies in time series
* Performs well for multi-horizon forecasting

### 🔹 1D Convolutional Neural Network (CNN)

* Captures short-term patterns
* Faster training compared to LSTM

---

## 📏 Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Percentage Error (MAPE)

---

## 📈 Results & Insights

* LSTM outperformed CNN for longer forecast horizons
* CNN performed well for short-term predictions
* Prediction error increased with forecast horizon due to market volatility

---

## 💼 Business Use Cases

* 📊 Crypto Trading Platforms → Short-term signals
* 🤖 Algorithmic Trading → Multi-horizon decision making
* ⚠️ Risk Management → Volatility estimation
* 📉 Investment Dashboards → Predictive insights

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* TensorFlow / Keras
* Matplotlib / Seaborn
* Scikit-learn

---

## 📂 Project Structure

```
CryptoCast/
│── CryptoCast_Bitcoin_Forecasting.ipynb
│── dataset.csv
│── README.md
```

---

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/CryptoCast-Bitcoin-Forecasting.git
   ```

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook
   ```bash
   jupyter notebook
   ```

---

## 🔮 Future Improvements

* Implement Transformer-based models
* Add real-time prediction pipeline
* Deploy using Streamlit dashboard

---

## 👨‍💻 Author

Shrinidhi Seshan

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
