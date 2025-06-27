# 📈 Stock Price Prediction Using Machine Learning

This project implements a simple machine learning-based algorithm to predict the **next day's stock opening and closing prices** using historical data (Open and Close values). The model is built using **TensorFlow**, **Pandas**, **NumPy**, and **scikit-learn**, and demonstrates data preprocessing, normalization, model training, and prediction.

---

## 🛠️ Technologies Used

- Python 3.x  
- TensorFlow  
- scikit-learn  
- Pandas  
- NumPy  
- Jupyter Notebook

---

## 📂 Dataset

The model expects a CSV file (`.csv`) with at least two columns:
- `Open`: Opening price of the stock
- `Close`: Closing price of the stock

📌 Make sure your CSV file has no missing values in these columns.

---

## 🔍 Features

- 📁 File upload and loading of stock data
- 🧹 Data cleaning and validation
- ⚖️ Normalization using MinMaxScaler
- 🧠 Training two neural networks:
  - One to predict next day’s `Open` price
  - One to predict next day’s `Close` price
- 📉 Predictions are denormalized to reflect real-world values
- ⏱️ Time taken for prediction is tracked and displayed

---


