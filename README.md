# customer_churn_prediction
Machine Learning project to analyze and predict customer churn

# 📊 Customer Churn Analysis - Telecom Company

This project aims to analyze customer churn behavior for a telecom company **Neo**. We explore customer data, apply data visualization, and implement multiple machine learning models to predict churn.

---

## 🧠 Problem Statement

The telecom company “Neo” is facing **customer churn**. You are a data scientist responsible for analyzing the customer churn dataset and providing insights to help reduce customer loss.

---

## 📁 Dataset

- **Name**: `customer_churn.csv`
- **Source**: Internal company data (sampled for this project)
- **Records**: 7043 rows, 21 columns

---

## 🛠️ Tools & Libraries

- Python (Jupyter Notebook)
- NumPy & Pandas
- Matplotlib & Seaborn
- scikit-learn (for ML models)

---

## ✅ Tasks Performed

### 🔹 A) Data Manipulation

- Extracted specific columns (e.g., 5th, 15th)
- Filtered customers based on conditions like:
  - Male senior citizens using electronic check
  - Tenure > 70 or Monthly Charges > $100
  - Two-year contract with mailed check & churn = Yes
- Sampled random 333 records
- Counted churn value occurrences

---

### 📊 B) Data Visualization

- Bar plot for `InternetService` distribution  
- Histogram for `Tenure` distribution  
- Scatter plot for `MonthlyCharges` vs `Tenure`  
- Boxplot for `Tenure` vs `Contract` type  

All plots saved inside the notebook and optionally in `visualizations/`.

---

### 📈 C) Linear Regression

- Built a model to predict **Monthly Charges** using **Tenure**
- Split dataset: 70% train / 30% test
- Calculated RMSE and prediction errors

---

### ✅ D) Logistic Regression

- Model 1 (Simple): `MonthlyCharges` → `Churn`
- Model 2 (Multiple): `MonthlyCharges`, `Tenure` → `Churn`
- Accuracy scores and confusion matrices included

---

### 🌳 E) Decision Tree

- Model: `Tenure` → `Churn`
- Split: 80% train / 20% test
- Output: Confusion Matrix & Accuracy

---

### 🌲 F) Random Forest

- Model: `MonthlyCharges`, `Tenure` → `Churn`
- Split: 70% train / 30% test
- Output: Confusion Matrix & Accuracy

---

## 📂 Project Structure

