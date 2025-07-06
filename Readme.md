# 🏦 Bank Customer Churn Prediction

This machine learning project predicts whether a customer will **churn (leave the bank)** based on demographic and behavioral data. The goal is to help banks proactively identify and retain valuable customers.

---

## 📂 Dataset Overview

The dataset includes the following features:

- **Demographic**: `age`, `gender`, `country`
- **Behavioral**: `credit_score`, `tenure`, `balance`, `products_number`, `estimated_salary`
- **Target Variable**: `churn` (1 = customer left, 0 = retained)

---

## 🛠️ Tech Stack

- **Languages**: Python
- **Libraries**:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualization
  - `scikit-learn` for preprocessing, SVC, and metrics
  - `xgboost` for gradient boosting classification

---

## 📊 ML Models Used

### 1. **XGBoost Classifier**
- Tuned with `GridSearchCV`
- Achieved:
  - **Recall (Churners)**: 0.75
  - **F1-Score (Churners)**: 0.61

### 2. **Support Vector Classifier (SVC)**
- Used `RBF` kernel with class weighting
- Achieved:
  - **Recall (Churners)**: 0.75
  - **F1-Score (Churners)**: 0.59

---

## Why more Focus on Recall?
