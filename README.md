# Rainfall-Prediction-using-Linear-Regression
## 📌 Overview
This project predicts **rainfall** using **Linear Regression**, a fundamental machine learning algorithm.  
It uses a **Kaggle dataset** containing weather data (temperature, humidity, Rainfall, etc.) to predict rainfall values.  
The aim is to build a model that can assist in weather forecasting and agricultural planning.

---

## 📊 Dataset
- **Source**: [Kaggle - Rainfall Prediction Dataset]
- Contains multiple weather parameters:
  - Minimum & Maximum Temperature
  - Humidity9am and Humidity9pm
  - Rainfall (target variable)

---

## 🧠 Theory: Linear Regression
**Linear Regression** is a supervised learning algorithm used for predicting continuous values.  
It fits a straight line (`y = mx + c`) to the data by minimizing the error between predicted and actual values using **Least Squares Method**.  

In this project:
- Features (X): Weather attributes
- Target (y): Rainfall amount
- Model: Simple/Multiple Linear Regression


```bash
pip install numpy pandas matplotlib scikit-learn
