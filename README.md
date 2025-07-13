# ☁️ Weather Data Analysis & Forecasting using Machine Learning

This project aims to analyze and predict weather conditions using historical data. The dataset includes key meteorological features such as temperature, humidity, pressure, and more. The goal is to evaluate and compare several regression models to identify patterns and forecast future temperatures effectively.

---

## 🎯 Objectives

- Explore the statistical properties of weather data
- Clean and preprocess the dataset
- Build and compare multiple regression models
- Evaluate models using standard performance metrics
- Visualize predictions vs. actual data

---

## 📁 Dataset

- **Source**: weatherHistory.csv  
- **Size**: ~10 years of hourly weather data  
- **Features**: Temperature, Humidity, Pressure, Summary, etc.

---

## 📊 Models Used

| Model              | MAE   | MSE   | RMSE  | R² Score |
|--------------------|-------|-------|--------|----------|
| Linear Regression  | 2.65  | 12.12 | 3.48   | 0.94     |
| Ridge Regression   | 2.67  | 12.20 | 3.49   | 0.94     |
| Lasso Regression   | 2.74  | 12.53 | 3.53   | 0.93     |
| Decision Tree      | 0.00  | 0.00  | 0.00   | 1.00     |
| Random Forest      | **1.08**  | **2.12**  | **1.46**   | **0.98**     |

> ✅ **Best Overall Model:** Random Forest – strong generalization with low error and high accuracy.

---

## 🧰 Technologies Used

| Tool/Library     | Purpose                            |
|------------------|------------------------------------|
| Pandas           | Data analysis and manipulation     |
| NumPy            | Numerical operations               |
| Matplotlib / Seaborn | Data visualization            |
| Scikit-learn     | Machine learning models and metrics |
