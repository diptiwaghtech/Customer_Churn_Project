# 📊 Telco Customer Churn Prediction

## Project Overview

This project aims to predict customer churn in a telecommunications company using Machine Learning techniques. Customer churn refers to customers discontinuing their telecom services. Early identification of potential churners helps organizations improve retention strategies and reduce revenue loss.

The project includes data cleaning, exploratory data analysis, feature engineering, class imbalance handling using SMOTE, model training, evaluation, and comparison of multiple classification algorithms.

---

## Business Problem

Customer retention is crucial for telecom companies. Predicting churn enables businesses to:

* Identify customers at risk of leaving
* Improve customer retention strategies
* Reduce revenue loss
* Increase customer lifetime value
* Support data-driven decision making

---

## Dataset

Dataset: Telco Customer Churn Dataset

Features include:

* Customer demographics
* Service subscriptions
* Internet services
* Contract information
* Payment methods
* Monthly charges
* Total charges
* Churn status

### Target Variable

* Churn (Yes / No)

---

## Project Workflow

### 1. Data Understanding

* Dataset exploration
* Data type inspection
* Missing value analysis

### 2. Data Cleaning

* Removed CustomerID column
* Handled missing values in TotalCharges
* Converted TotalCharges to numeric format

### 3. Exploratory Data Analysis (EDA)

* Churn distribution analysis
* Numerical feature analysis
* Categorical feature analysis
* Correlation heatmap
* Box plots and visualizations

### 4. Data Preprocessing

* Label Encoding
* Feature transformation
* Train-Test Split

### 5. Handling Class Imbalance

* SMOTE (Synthetic Minority Oversampling Technique)

### 6. Model Training

The following classification models were trained and evaluated:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier

### 7. Model Evaluation

Performance metrics used:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score
* Classification Report

---

## Results

Model comparison was performed across multiple classification algorithms.

**Best Performing Model:** Random Forest Classifier

The model demonstrated superior performance in predicting customer churn compared to the other evaluated models.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Imbalanced-Learn (SMOTE)
* Jupyter Notebook

---

## Repository Structure

```text
Telco-Customer-Churn-Prediction/
│
├── Churn_Project_ML.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── README.md
└── requirements.txt
```

---

## Future Improvements

* Hyperparameter tuning
* Feature selection
* Model deployment using FastAPI
* Customer retention recommendation system
* Automated ML pipeline

