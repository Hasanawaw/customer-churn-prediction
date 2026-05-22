
# Customer Churn Prediction Project

## Project Overview

This is an end-to-end machine learning project focused on predicting customer churn for a telecom company.

The goal of this project is to identify customers who are likely to leave the company based on customer information, contract details, services, and payment behavior.

---

## Dataset

Dataset used:
- Telco Customer Churn Dataset

Target variable:
- Churn

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Cleaning
- Removed invalid values
- Fixed data types
- Handled hidden missing values

### 2. Exploratory Data Analysis (EDA)
- Churn distribution analysis
- Contract type analysis
- Monthly charges analysis
- Tenure analysis

### 3. Preprocessing
- OneHotEncoding
- StandardScaler
- ColumnTransformer
- Pipeline

### 4. Machine Learning Models
- Logistic Regression
- Random Forest Classifier
- Hyperparameter Tuning with GridSearchCV

### 5. Model Evaluation

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Final Results

### Best Business Model

Logistic Regression performed better for detecting churn customers compared to Random Forest.

Reason:
- Better recall for churn prediction
- Better business value for customer retention

---

## Most Important Features

- Tenure
- TotalCharges
- MonthlyCharges
- Contract Type

---

## Project Structure

```text
customer-churn-prediction/
│
├── data/
├── models/
├── customer-churn-project.ipynb
└── README.md


