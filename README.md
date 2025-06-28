# 📈 Stock Price Prediction using Machine Learning

This project demonstrates a basic approach to predict stock prices using historical data and machine learning techniques.  
The goal is to forecast future closing prices of a selected stock using regression models.

---

## 🔍 Overview

- 📅 Uses historical stock price data (e.g., from Yahoo Finance)
- 📊 Explores and visualizes data trends
- 🤖 Trains ML models (like Linear Regression)
- 📈 Evaluates and plots predicted vs. actual prices
- 💾 Written in a single Jupyter Notebook with outputs included

---

## 🛠️ Features

- Download historical stock data using `yfinance`
- Create features based on moving averages and time lags
- Train/Test split for model evaluation
- Model: **Linear Regression**
- Visualization: Real vs. Predicted Price comparison

---

## 📂 File Structure

stock-prediction/

│

├── README.md # You're here

└── stock_prediction.ipynb # Jupyter notebook with code and output

---


---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/stock-prediction-ml.git
cd stock-prediction-ml
```

---

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install yfinance pandas scikit-learn matplotlib seaborn
```

---

###3. Run the Notebook
Open stock_prediction.ipynb in Jupyter Lab/Notebook or any compatible environment.
