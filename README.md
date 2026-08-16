# 🏠 House Price Prediction using Machine Learning

A machine learning project that predicts house prices using property features from the Kaggle House Prices dataset.

The project compares **Linear Regression** and **Random Forest Regressor** models and selects the better-performing model based on evaluation metrics.

---

## 📌 Project Overview

The goal of this project is to build a machine learning model that can estimate house sale prices based on important property characteristics.

The workflow includes:

- Data loading and cleaning
- Feature selection
- Train-test splitting
- Model training
- Model evaluation
- Model comparison
- House price prediction
- Saving the trained model

---

## 📊 Dataset

**Dataset:** Kaggle House Prices Dataset

- Original dataset: **1,460 houses**
- Original features: **81 columns**
- Selected features: **9**
- Target variable: **SalePrice**

---

## 🔍 Features Used

The model uses the following property features:

| Feature | Description |
|---|---|
| `LotArea` | Lot size in square feet |
| `OverallQual` | Overall material and finish quality |
| `OverallCond` | Overall condition of the house |
| `YearBuilt` | Original construction year |
| `GrLivArea` | Above-ground living area |
| `FullBath` | Number of full bathrooms |
| `BedroomAbvGr` | Number of bedrooms |
| `TotRmsAbvGrd` | Total rooms above ground |
| `GarageCars` | Garage capacity |

---

## 🤖 Machine Learning Models

Two regression models were trained and compared:

### 1. Linear Regression

R² Score: **0.7907**

### 2. Random Forest Regressor

R² Score: **0.8877**

Random Forest performed better than Linear Regression and was selected as the final model.

---

## 📈 Model Performance

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | $25,573.63 | $40,069.53 | 0.7907 |
| Random Forest | $19,187.05 | $29,344.86 | **0.8877** |

### 🏆 Best Model

**Random Forest Regressor**

The Random Forest model achieved an R² score of **0.8877**, meaning it explained approximately **88.77% of the variation** in house sale prices on the test set.

---

## 💰 Example Prediction

For a sample property with:

- Lot Area: 845 sq ft
- Overall Quality: 7
- Overall Condition: 5
- Year Built: 2003
- Living Area: 1,710 sq ft
- Full Bathrooms: 2
- Bedrooms: 3
- Total Rooms: 8
- Garage Capacity: 2 cars

The model predicted:

### 🏠 **$148,677.45**

---

## 📊 Visualizations

The notebook includes:

- Model R² score comparison
- Actual vs Predicted house prices

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Google Colab
- Git & GitHub

---

## 📁 Project Structure

```text
house_price_prediction/
│
├── house_price_prediction.ipynb
├── house_price_model.pkl
└── README.md