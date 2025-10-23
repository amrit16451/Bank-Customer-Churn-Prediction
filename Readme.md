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
  - **Recall (Churners)**: 0.79
  - **Model Accuracy**: 77%


---

## Why more Focus on Recall?
🧠 Real-world Implication:
If recall is low, you're missing actual churners, and the bank loses those customers.

If precision is low, you might wrongly contact some loyal customers, but that’s less costly than losing a real churner.
