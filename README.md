# Customer Churn Prediction Analytics

**End-to-end machine learning project predicting customer churn using classification algorithms.**  
Includes data preprocessing, feature engineering, model training, evaluation, and dashboard visualization.

---

## Project Overview

Customer churn prediction helps companies identify which customers are likely to leave a service.  
Predicting churn allows companies to take preventive actions and retain valuable customers.

- Problem Type: **Classification**  
- Target Variable: `Churn` (Yes / No)  
- Tools & Libraries: `Python`, `Pandas`, `NumPy`, `Scikit-learn`, `Matplotlib`, `Seaborn`, `Streamlit`  

---

## Folder Structure
Customer-Churn-Prediction-Analytics/
│
├── data/ # Original and cleaned datasets
│ └── churn_data.csv
│
├── notebooks/ # Jupyter notebooks
│ ├── 01_data_exploration.ipynb
│ ├── 02_data_preprocessing.ipynb
│ ├── 03_feature_engineering.ipynb
│ └── 04_model_training.ipynb
│
├── scripts/ # Python scripts
│ ├── preprocess.py
│ ├── train_model.py
│ └── evaluate_model.py
│
├── models/ # Saved trained model
│ └── churn_model.pkl
│
├── dashboard/ # Streamlit / Dash app
│ └── churn_dashboard.py
│
├── requirements.txt # Python dependencies
└── README.md


---

## 🔹 Features

- Data cleaning & preprocessing  
- Handling missing values & categorical encoding  
- Feature engineering (tenure, monthly charges, etc.)  
- Classification models: Logistic Regression, Random Forest, XGBoost  
- Model evaluation: Accuracy, Precision, Recall, F1-score, Confusion Matrix  
- Feature importance visualization  
- Interactive **dashboard** for predicting churn probability  

---

## 🔹 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction-Analytics.git
cd Customer-Churn-Prediction-Analytics

Install dependencies:

pip install -r requirements.txt

🔹 How to Run the Dashboard
streamlit run dashboard/churn_dashboard.py

Dataset

Dataset: Telco Customer Churn Dataset (Kaggle)
Columns include: customerID, gender, SeniorCitizen, Partner, Dependents, tenure, MultipleLines, InternetService, OnlineSecurity, MonthlyCharges, TotalCharges, Churn

Author

Pooja Parashuram Bajantri – Data Science Enthusiast / Aspiring Data Engineer