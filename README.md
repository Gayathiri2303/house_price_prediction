# 🏠 House Price Prediction using Machine Learning

A machine learning project that predicts house prices using property features from the Kaggle House Prices dataset.

## 📌 Project Overview

This project compares two machine learning models:

- Linear Regression
- Random Forest Regressor

The Random Forest model performed better and achieved an R² score of **0.8877**.

## 📊 Dataset

The project uses the Kaggle House Prices dataset.

Dataset size after cleaning:

- 1,460 houses
- 9 prediction features

## 🔍 Features Used

- Lot Area
- Overall Quality
- Overall Condition
- Year Built
- Living Area
- Full Bathrooms
- Bedrooms
- Total Rooms
- Garage Capacity

## 🤖 Model Performance

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | $25,573.63 | $40,069.53 | 0.7907 |
| Random Forest | $19,187.05 | $29,344.86 | 0.8877 |

## 🏆 Best Model

Random Forest Regressor was selected because it achieved the highest R² score.

## 💰 Example Prediction

For a sample property, the model predicted:

**$148,677.45**

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Google Colab

## 📁 Project Files

- `house_price_prediction.ipynb` — Complete machine learning notebook
- `house_price_model.pkl` — Trained Random Forest model
- `README.md` — Project documentation