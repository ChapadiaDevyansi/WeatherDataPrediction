# 🌦️ Weather Data Prediction

Predicts whether it will rain in a given hour using hourly weather data and machine learning. Built as part of a data analytics internship project.

## 📊 Dataset
Hourly weather observations (Jan 2025 – Jul 2026), 13,368 records — temperature, humidity, pressure, wind speed, cloud cover, and rainfall.

## 🤖 Models & Results

| Model | Accuracy | F1-Score |
|---|---|---|
| Logistic Regression | 88.03% | 65.67% |
| Decision Tree | 87.28% | 63.68% |
| **Random Forest** ✅ | **91.10%** | **72.13%** |

Random Forest performed best and was selected as the final model. Top predictors: **Cloud Cover, Surface Pressure, Humidity**.

## 📈 Dashboard
Interactive Power BI dashboard with weather overview and model results pages.

## 🛠️ Tech Stack
Python · Pandas · Scikit-learn · Matplotlib/Seaborn/Plotly · Power BI · Jupyter Notebook
