# 🏠 House Price Prediction – Advanced Regression (Ames Dataset)

This project predicts house sale prices using advanced regression techniques on the Ames Housing Dataset. It's part of the [Kaggle competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

## 📊 Problem Statement
Predict the final price of homes in Ames, Iowa based on various features such as quality, area, basement, garage, etc.

## 🧰 Techniques Used

- Exploratory Data Analysis (EDA)
- Skewness correction (log transformation)
- Missing value imputation using domain logic
- One-hot encoding
- Feature scaling (StandardScaler)
- Regression models:
  - Linear Regression
  - Lasso (L1)
  - Ridge (L2)
  - Random Forest
  - XGBoost (best performing)

## ✅ Best Model: XGBoost
Achieved a **public score of 0.13342 RMSE** on Kaggle.

## 📁 Files
- `house_price_prediction.ipynb`: Full notebook
- `submission.csv`: Prediction file submitted to Kaggle
- `data_description.txt`: Official feature definitions

## 📈 Results Summary
| Model            | RMSE (CV)  |
|------------------|------------|
| Linear Regression | NaN (unstable) |
| Ridge            | 0.1582     |
| Lasso            | 0.1612     |
| Random Forest    | 0.1448     |
| **XGBoost**      | **0.1303** ✅ |

## 📸 Visuals
Key screenshots include:
- Distribution of SalePrice (before/after log)
- Correlation heatmaps
- Missing value bars
- Kaggle submission confirmation

## 💡 Future Improvements
- Hyperparameter tuning (GridSearchCV)
- Ensemble stacking
- Feature importance visualization
