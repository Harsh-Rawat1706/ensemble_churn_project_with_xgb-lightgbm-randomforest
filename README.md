# 🔄 Customer Churn Prediction using Ensemble Models

This project predicts customer churn using an ensemble of machine learning models: **Random Forest**, **XGBoost**, and **LightGBM**. The goal is to identify customers likely to leave a service, helping businesses improve retention strategies.

---

## 📊 Dataset

- The dataset includes features like customer demographics, service usage, and contract information.
- The target variable is `Churn`, indicating whether a customer has churned (`Yes`) or not (`No`).

---

## ⚙️ Preprocessing Steps

- Handled missing values and removed duplicate rows.
- Encoded categorical variables using `LabelEncoder`.
- Transformed binary columns (e.g., `SeniorCitizen`) to categorical (`Yes`/`No`).
- Standardized numerical features using `StandardScaler`.
- Visualized churn distribution and feature relationships using seaborn/matplotlib.

---

## 🧠 Models Used

The following models were trained and evaluated:

- 🌲 **Random Forest Classifier**
- ⚡ **XGBoost Classifier**
- 🌿 **LightGBM Classifier**

Each model was trained on the processed data, and predictions were evaluated using:

- ✅ Accuracy Score
- 📉 Confusion Matrix
- 📃 Classification Report (Precision, Recall, F1-score)

---

## 📈 Evaluation Metrics

Each model's performance was compared using:

- **Confusion Matrix**
- **Classification Report**
- **Accuracy Score**

Plots were generated to visually compare model performance.

---

## 📌 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Harsh-Rawat1706/ensemble_churn_project_with_xgb-lightgbm-randomforest.git
   
