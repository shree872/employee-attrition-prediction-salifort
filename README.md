# employee-attrition-prediction-salifort
This repository contains a Machine Learning project predicting employee attrition using data analysis, feature engineering, and classification models.

# Employee Attrition Prediction using Machine Learning (Salifort Motors)

## 📌 Project Overview

This project develops a predictive machine learning model to identify employees at risk of attrition. Using HR analytics and employee behavioral data, the project uncovers key drivers of employee turnover and provides actionable insights to improve retention strategies.

## 🎯 Business Problem

High employee attrition leads to increased hiring costs, productivity loss, and operational inefficiencies.
The objective is to leverage data-driven insights to **predict employee attrition** and support proactive retention decisions at Salifort Motors.

---

## 📊 Dataset Description

* HR analytics dataset containing employee-level data
* Features include:

  * Department
  * Number of projects
  * Average monthly hours
  * Tenure
  * Salary level
  * Work evaluation metrics

---

## 🔍 Exploratory Data Analysis (EDA)

* Performed data cleaning, handling missing values, and duplicate removal
* Detected and analyzed **outliers in tenure and workload variables**
* Explored relationships between employee workload, tenure, and attrition
* Identified **imbalanced distribution of employees leaving vs staying**

---

## 📈 Key Insights

* ⏳ **Tenure & Attrition:**
  Employees with either very low or very high tenure show higher attrition risk, indicating onboarding and burnout phases.

* 🔥 **Workload Impact:**
  High number of projects and excessive monthly working hours are strongly associated with employee burnout and higher attrition.

* 🏢 **Department-Level Risk:**
  Certain departments exhibit significantly higher turnover, highlighting the need for targeted retention strategies.

* 💰 **Compensation Influence:**
  Lower salary tiers are more likely to experience attrition, indicating compensation as a key retention factor.

* ⚖️ **Work-Life Balance Signal:**
  Employees with extreme working hours and workload imbalance are more likely to leave.

---

## 🤖 Machine Learning Model

* **Model Type:** Classification Model (e.g., Random Forest / Logistic Regression)

* **Techniques Used:**

  * Feature Engineering
  * Data Preprocessing
  * Model Training & Validation
  * Performance Evaluation

* **Evaluation Metrics:**

  * Accuracy: XX%
  * Recall: XX%
  * Precision: XX%

---

## 📊 Model Insights

![Feature Importance](images/feature_importance.png)

* Workload-related features (projects, hours) are among the **top predictors of attrition**
* Tenure and salary significantly influence model predictions
* Behavioral patterns are more predictive than static attributes

---

## 📣 Business Recommendations

* 🚨 **Prevent Employee Burnout:**
  Monitor workload and reduce excessive project assignments

* 📉 **Optimize Work Hours:**
  Implement policies to improve work-life balance

* 🎯 **Target High-Risk Employees:**
  Use predictive model to identify and retain at-risk employees early

* 💰 **Review Compensation Strategy:**
  Improve salary structures for lower-tier employees

* 🏢 **Department-Specific Interventions:**
  Focus retention efforts on departments with high attrition rates

---

## 📁 Project Files

* [📓 ML Notebook](notebooks/employee_attrition_prediction_model.ipynb)

---

## 🚀 Tools & Technologies

Python | Pandas | NumPy | Matplotlib | Scikit-learn | Machine Learning | Data Analysis | Predictive Modeling

---

## 🔑 Keywords

Employee Attrition | HR Analytics | Predictive Modeling | Machine Learning | Classification | Feature Engineering | Data Analysis | Workforce Analytics

