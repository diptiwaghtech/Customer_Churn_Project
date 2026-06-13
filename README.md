# Customer Churn Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on predicting customer churn using Machine Learning techniques. The goal is to identify customers who are likely to leave a service so that businesses can take proactive retention measures.

The project includes:
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Handling class imbalance using SMOTE
- Training multiple classification models
- Model evaluation and comparison
- Cross-validation and performance metrics

---

## 📂 Dataset
The project uses the **Telco Customer Churn Dataset** containing customer demographics, account information, subscribed services, and churn status.

### Target Variable
- **Churn**
  - Yes → Customer left
  - No → Customer retained

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Imbalanced-Learn (SMOTE)
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Collection
- Load customer churn dataset
- Inspect structure and data types

### 2. Data Cleaning
- Remove unnecessary columns
- Handle missing values
- Convert categorical variables

### 3. Exploratory Data Analysis (EDA)
- Customer demographics analysis
- Service subscription analysis
- Churn distribution analysis
- Correlation analysis

### 4. Feature Engineering
- Label Encoding
- Data transformation
- Feature selection

### 5. Handling Imbalanced Data
- SMOTE (Synthetic Minority Over-sampling Technique)

### 6. Model Building
The following classification models are evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Naive Bayes
- Gradient Boosting

### 7. Model Evaluation
Performance is measured using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Cross Validation

---

## 📈 Key Objectives

- Predict customer churn accurately
- Identify important churn-driving factors
- Compare multiple machine learning algorithms
- Build a scalable churn prediction pipeline

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
