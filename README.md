# Sales Forecasting Project

This project predicts daily retail sales using Linear Regression and time-based feature engineering. Built for business planning and inventory decisions.

## 📊 What is included
- **Data Generation**: Synthetic daily sales with trend + seasonality
- **Feature Engineering**: Trend, weekly pattern, 7-day rolling average, lag_7 values
- **Model**: Linear Regression using Scikit-learn
- **Evaluation**: MAE and RMSE on 6 months test data
- **Visualization**: Business-friendly plots with Matplotlib

## 📈 Model Results
- **MAE: 7.23** - Predictions are off by ~7 units on average
- **RMSE: 9.15** - Captures impact of larger errors

These results show the model can forecast sales trends reliably for planning.

## 🛠️ Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Jupyter Notebook

## ⚙️ Requirements
Install the required Python libraries:

```bash
pip install -r requirements.txt
