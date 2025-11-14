# Calories Burnt Prediction Using XGBoost Pipeline

This project builds a machine learning model to predict calories burnt during physical activity based on user data such as age, gender, height, weight, heart rate, and body temperature.

---

## Project Overview

The workflow includes:

1. **Data Preprocessing**  
   - Encoding categorical variables (e.g., Gender)  
   - Scaling numeric features (e.g., Age, Height, Weight, Duration, Heart Rate, Body Temperature)

2. **Model Training**  
   - Using XGBoost regression (`XGBRegressor`) to predict calories burnt.

3. **Pipeline Integration**  
   - Combining preprocessing and model training in a single scikit-learn `Pipeline` for easy training and prediction.

---

## Installation

Make sure you have the required libraries installed:

```bash
pip install numpy pandas scikit-learn xgboost



