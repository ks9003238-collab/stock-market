# 📊 Stock Market Trend Prediction using Machine Learning

## 🚀 Project Overview

This project focuses on analyzing stock market data and predicting next-day market direction (UP/DOWN) using machine learning techniques. It applies time-series feature engineering and avoids data leakage to ensure realistic predictions.

---

## 🎯 Objective

- Analyze historical stock data  
- Identify trends and patterns  
- Predict future market behavior (UP 📈 / DOWN 📉)

---

## 📁 Dataset

The dataset contains historical stock data including:
- Date  
- Open, High, Low, Close prices  
- Volume  

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🔧 Project Workflow

### 1. Data Preprocessing
- Converted Date column to datetime format  
- Removed duplicates and invalid values  
- Sorted data based on time  

---

### 2. Feature Engineering

Created time-series features:

- Lag Features (Lag_1, Lag_2, Lag_3)  
- Moving Averages (MA_10, MA_50)  
- Daily Returns  
- Volatility  

Note: Only past data is used to avoid data leakage.

---

### 3. Target Variable

Target = 1 (UP) → if next day's price is higher  
Target = 0 (DOWN) → if next day's price is lower  

---

### 4. Model Building

- Used Random Forest Classifier  
- Applied time-based train-test split (no random shuffling)  

---

### 5. Model Evaluation

- Accuracy Score  
- Classification Report  
- Feature Importance Analysis  

---

## 📈 Results

- Achieved reliable prediction accuracy for market direction  
- Identified important features such as:
  - Moving averages  
  - Lag values  
  - Volatility  

---

## 🔮 Prediction Output

The model predicts:
- 📈 Market will go UP  
- 📉 Market will go DOWN  

Also provides probability scores for better decision-making.

---

## 🚨 Key Learnings

- Importance of avoiding data leakage  
- Proper handling of time-series data  
- Feature engineering improves model performance  
- Stock prediction requires careful validation  

---

## 🧠 Future Improvements

- Add technical indicators (RSI, MACD)  
- Use LSTM for deep learning  
- Deploy using Streamlit  
- Build trading strategy (buy/sell signals)  

---

👨‍💻 Author

Kishor Solanki
Email: solankikishor8546@gmail.com
