# 🏦 Mudra Loan Risk Prediction

This project aims to develop a machine learning model that predicts the **risk associated with granting Mudra loans**. Using historical data and statistical techniques, we assess loan applicants based on key financial and categorical variables to aid in more informed lending decisions.

---

## 📌 Project Objective

To predict whether a loan applicant is **risky or not risky**, thereby enabling financial institutions to reduce **Non-Performing Assets (NPAs)** and improve the **quality of credit decisions** under the Pradhan Mantri Mudra Yojana (PMMY).

---

## 📁 Dataset

The dataset consists of anonymized historical records of loan applications with multiple features such as:

- **Loan Amount**
- **Disbursed Amount**
- **Loan Term**
- **Gender**
- **Category**
- **Credit History**
- **Region**
- **State**
- **Employment Status**
- **Risk Label (Target)**

> Note: For confidentiality, data identifiers have been removed or masked.

---

## ⚙️ Workflow

The entire workflow follows the standard **CRISP-DM** methodology:

### 1. 🧠 Business Understanding
Understanding the domain and identifying that improper lending can lead to NPAs.

### 2. 🧹 Data Preparation
- Handling missing values
- Data cleaning
- Feature transformation and encoding
- Removing duplicates

### 3. 📊 Exploratory Data Analysis
- Histograms and boxplots for numerical features
- Pie and bar charts for categorical distributions
- Correlation heatmap

### 4. 🧮 Feature Engineering
- Label Encoding and OneHotEncoding
- Handling imbalance using **SMOTE**
- Normalization or standard scaling

### 5. 📈 Modeling
Models used:
- Logistic Regression
- Knn (kNerarest Neighbor)
- Random Forest Classifier
- Decision Tree

### 6. 📊 Model Evaluation
Metrics evaluated:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Curve

### 7. ✅ Final Model Selection
Best-performing model is chosen based on cross-validation performance and business interpretability.

---

## 🔍 Key Features

- Dynamic visualizations for feature insights
- Automated data preprocessing pipeline
- Modular and scalable code structure in Jupyter Notebook
- Supports extension for other classification use cases

---

## 🧪 Installation & Usage

1. Clone the repository:

```bash
git clone https://github.com/Aksharagupta12555/mubra_loans
