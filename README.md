# House-Price-Prediction-Kaggle-
Prodigy Task 1 
# 🏠 House Price Prediction - Advanced Regression Techniques

![Kaggle Badge](https://img.shields.io/badge/Kaggle-House%20Prices-blue)  
![Python](https://img.shields.io/badge/Made%20with-Python-yellow?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Overview

This project is a solution to the famous **"House Prices - Advanced Regression Techniques"** competition hosted on Kaggle. The goal is to predict the **final price of residential homes** in Ames, Iowa, based on 79 explanatory variables describing various aspects of residential homes.

The dataset is considered a benchmark for regression problems and is widely used for learning feature engineering, model tuning, and stacked models.

---

## 🚀 Project Highlights

- ✅ Comprehensive EDA with visualizations  
- ✅ Outlier detection and handling  
- ✅ Feature engineering and encoding  
- ✅ Missing value imputation strategies  
- ✅ Model comparison: Linear Regression, Ridge, Lasso, XGBoost, and Stacking  
- ✅ Kaggle submission file generation

📦house-price-prediction/
┣ 📄 house_price_notebook.ipynb <- Main Kaggle notebook
┣ 📄 submission.csv <- Final submission to Kaggle
┣ 📄 requirements.txt <- List of required Python packages
┣ 📄 README.md <- You're here!


---

## 📊 Exploratory Data Analysis (EDA)

- Checked target variable skewness
- Handled numerical and categorical features separately
- Identified key correlations with sale price
- Visualized:
  - Heatmaps
  - Distribution plots
  - Box plots
  - Scatter plots

---

## 🛠 Feature Engineering

- Imputed missing values with:
  - Mode / Median / Custom values
- Created new features:
  - TotalSF = Total square footage
  - Age = YrSold - YearBuilt
- Applied log transformation on skewed features
- One-hot encoded categorical variables

---

## 🤖 Models Implemented

| Model              | CV Score (RMSE) | Notes                             |
|-------------------|------------------|-----------------------------------|
| Linear Regression | 0.1432           | Baseline                          |
| Ridge Regression  | 0.1304           | Reduced overfitting               |
| Lasso Regression  | 0.1291           | Effective feature selection       |
| XGBoost           | 0.1227           | Best single model                 |
| Stacking Regressor| 0.1189           | Final model used for submission  |

---

## 📈 Final Results

- Best public score: **0.1189 (RMSE)**
- Model: **Stacked Regressor (Lasso + XGBoost + Ridge)**
- Ranked in **top X%** on Kaggle leaderboard *(update this based on your rank)*

---

## 📦 Dependencies

You can install all necessary packages with:

```bash
pip install -r requirements.txt

Key libraries used:

pandas, numpy

matplotlib, seaborn

scikit-learn

xgboost

💡 Future Improvements
Hyperparameter tuning using GridSearchCV / Optuna

Automated pipeline using scikit-learn pipelines

Deployment as a web app using Flask or Streamlit

🧑‍💻 Author
Sai Shanmukh
📬 LinkedIn www.linkedin.com/in/sai-shanmukh-667b36290
📧 saishanmukh74@gmail.com

