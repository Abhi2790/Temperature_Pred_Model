# 🌡️ Temperature Prediction Model (India Weather 2000–2024)

This project predicts **next-day maximum temperature** for Indian cities using machine learning regression models.  
It also includes a **binary classification** task to predict whether the temperature will exceed **30°C**.  

## 📌 Features
- Data preprocessing (date handling, missing values, feature engineering)  
- Regression models: **Ridge, Lasso, ElasticNet**  
- Classification model: **Logistic Regression**  
- Model evaluation with **R², RMSE, Accuracy, Classification Report, Confusion Matrix**  
- Performance visualization (line plots for R² & RMSE)  
- Example prediction for new weather input  

---

## 📂 Dataset
- File: `DATA_CSV/india_2000_2024_daily_weather.csv`  
- Contains daily weather data for Indian cities (2000–2024).  
- Key features used:
  - `temperature_2m_max`, `temperature_2m_min`
  - `apparent_temperature_max`, `apparent_temperature_min`
  - `precipitation_sum`, `rain_sum`
  - `weather_code`, `wind_speed_10m_max`
  - `wind_gusts_10m_max`, `wind_direction_10m_dominant`

The target variable is **next-day maximum temperature** (`target_temp_max`).  

---

## Requirements

-Python 3.8+

-numpy, pandas, matplotlib

-scikit-learn

## ⚙️ Installation
Clone this repository and install dependencies:  

```bash
git clone https://github.com/Abhi2790/Temperature_Pred_Model.git
cd Temperature_Pred_Model
pip install -r requirements.txt

---

## 👨‍💻 Author

-Abhishek Kumar
-MCA (AI/ML) | ML & Data Science Enthusiast


