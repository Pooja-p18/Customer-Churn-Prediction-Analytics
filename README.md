# 📊 Customer Churn Prediction Analytics

## 🚀 Project Overview

This project focuses on predicting customer churn using machine learning techniques.
The goal is to identify customers who are likely to leave a service so that businesses can take proactive actions to retain them.

---

## 🎯 Objective

* Analyze customer data to understand churn behavior
* Build and compare machine learning models
* Identify key factors influencing customer churn
* Provide actionable business insights

---

## 📂 Dataset

* **Source**: IBM Telco Customer Churn Dataset
* **Records**: 7043 customers
* **Features**: Customer demographics, services, billing, and usage patterns

---

## 🛠️ Tech Stack

* **Programming Language**: Python
* **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Tools**: Jupyter Notebook, Git, GitHub

---

## 📊 Project Workflow

### 1️⃣ Data Exploration

* Checked data types and missing values
* Analyzed class imbalance
* Visualized key patterns and distributions

---

### 2️⃣ Data Preprocessing

* Handled missing values
* Converted categorical variables to numerical
* Removed irrelevant columns
* Cleaned and structured dataset

---

### 3️⃣ Feature Engineering

* Created new features:

  * `tenure_group`
  * `avg_charges`
  * `charge_ratio`
  * `engagement_score`
* Improved model performance with meaningful features

---

### 4️⃣ Model Training

* Logistic Regression (Baseline Model)
* Random Forest Classifier

---

### 5️⃣ Model Evaluation

* Accuracy, Precision, Recall, F1-score
* Confusion Matrix
* ROC Curve & AUC Score

📈 Results:

* Logistic Regression AUC: **0.96**
* Random Forest AUC: **0.97** (Best Model)

---

## 🔍 Key Insights

* Customers with **high monthly charges** are more likely to churn
* Customers with **low tenure** (new users) have higher churn rates
* **High charge ratio** indicates higher churn probability
* Customers using **electronic check payments** churn more
* Higher **engagement and CLTV** reduce churn risk

---

## 🏆 Conclusion

Random Forest performed the best with high accuracy and AUC score, demonstrating strong capability in identifying churn patterns.
The model can help businesses take proactive actions to improve customer retention.

---

## 📁 Project Structure

```
Customer-Churn-Prediction-Analytics/
│── data/
│   ├── raw/
│   ├── cleaned_churn_data.csv
│   ├── featured_churn_data.csv
│
│── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_model_training.ipynb
│   ├── 05_model_evaluation.ipynb
│   ├── 06_feature_importance.ipynb
│
│── README.md
│── requirements.txt
```

---

## 💡 Future Improvements

* Hyperparameter tuning
* Deploy model using Flask/Streamlit
* Build interactive dashboard
* Try advanced models (XGBoost, LightGBM)

---

## 🙌 Author

**Pooja Parashuram Bajantri**
Aspiring Data Scientist | Python | Machine Learning

---
