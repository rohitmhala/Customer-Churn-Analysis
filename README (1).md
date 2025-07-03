
# 📊 Telecom Customer Churn Analysis

> An end-to-end exploratory data analysis (EDA) project to uncover key patterns and reasons behind customer churn in a telecom company.

---

## 📌 Project Objective

The main objective of this project is to identify factors influencing customer churn in a telecom business and to generate actionable insights using exploratory data analysis (EDA). By analyzing various customer attributes such as tenure, internet service type, contract duration, and billing information, this project helps in:

- Understanding the characteristics of customers who are likely to churn  
- Supporting data-driven decision-making for customer retention strategies  
- Visualizing trends through insightful plots and graphs

---

## 🗂 Dataset Overview

- **Name**: Telco Customer Churn  
- **Source**: Kaggle / IBM Sample Telecom Dataset  
- **Format**: CSV  
- **Size**: 7043 rows × 21 columns  
- **Features**:
  - Customer demographics (gender, senior citizen, partner, dependents)  
  - Service-related features (internet service, phone service, contract)  
  - Billing (monthly charges, total charges, payment method)  
  - Churn (target column)

---

## ❓ Questions Answered

This project explores the following key questions:

1. What percentage of customers have churned?  
2. Which gender is more likely to churn?  
3. Does being a senior citizen affect churn rate?  
4. How does contract type impact customer retention?  
5. Which internet service type is most associated with churn?  
6. Is there a relationship between tenure and churn?  
7. Do monthly charges or payment method influence churn?  
8. What are the most influential customer attributes in churn behavior?

---

## 🔍 Project Process

### 1. 📥 Data Loading
- Imported dataset with Pandas
- Checked shape, types, and missing values

### 2. 🧹 Data Cleaning
- Handled missing values (especially `TotalCharges`)
- Converted types and cleaned categorical columns

### 3. 📊 Univariate Analysis
- Used countplot/histplot to examine distributions

### 4. 📈 Bivariate Analysis
- Compared churn vs gender, contract type, internet, etc.

### 5. 🧠 Statistical Insights
- Grouped churn percentages by customer groups

### 6. 📉 Visualization
- Created bar, box, histogram, and stacked plots using Seaborn

### 7. 🧾 Summary & Insights
- Extracted key patterns for business recommendations

---

## 🔗 Key Deliverables

- 📘 Executive Summary  
- 📊 Jupyter Notebook  
- 📁 Dataset with churn labels

---

## 👨‍🎓 Author

**Rohit Mhala**  
*Data Science Student — EDA | Visualization | Business Insight*
