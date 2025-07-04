# **📊 Telecom Customer Churn Analysis**

An end-to-end exploratory data analysis (EDA) project to uncover key patterns and reasons behind customer churn in a telecom company.

---

## **📌 Project Objective**

The main objective of this project is to identify factors influencing customer churn in a telecom business and to generate actionable insights using exploratory data analysis (EDA). By analyzing various customer attributes such as tenure, internet service type, contract duration, and billing information, this project helps in:

* Understanding the characteristics of customers who are likely to churn

* Supporting data-driven decision-making for customer retention strategies

* Visualizing trends through insightful plots and graphs

---

## **🗂 Dataset Overview**

* **Name**: Telco Customer Churn

* **Source**: Kaggle / IBM Sample Telecom Dataset

* **Format**: CSV

* **Size**: 7043 rows × 21 columns

* **Features**:

  * Customer demographics (gender, senior citizen, partner, dependents)

  * Service-related features (internet service, phone service, contract)

  * Billing (monthly charges, total charges, payment method)

  * Churn (target column)

---

## **❓ Questions Answered**

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

## **🔍 Project Process**

The following step-by-step process was followed for conducting the analysis:

### **1\. 📥 Data Loading**

* Imported the dataset using **Pandas**

* Checked the shape, data types, and sample records

* Verified the presence of null or missing values

### **2\. 🧹 Data Cleaning**

* Removed or imputed missing values (especially in `TotalCharges`)

* Converted `TotalCharges` to a numeric type

* Transformed categorical variables into consistent formats

* Removed redundant or duplicate records (if any)

### **3\. 📊 Univariate Analysis**

* Analyzed the distribution of individual columns using:

  * `countplot` for categorical variables (e.g., gender, payment method)

  * `histplot` for continuous variables (e.g., monthly charges, tenure)

* Identified value imbalances (e.g., more customers with short tenure)

### **4\. 📈 Bivariate Analysis**

* Explored relationships between features and `Churn` using:

  * Grouped bar charts (`hue='Churn'`)

  * Box plots and violin plots

  * Cross-tabulations and percentages

* Compared churn rates across:

  * Contract types

  * Internet services

  * Payment methods

  * Gender and seniority

### **5\. 🧠 Statistical Insights**

* Calculated churn percentages by group:

  * E.g., churn rate among senior citizens \= 42%

* Measured effect of numerical variables (e.g., tenure and monthly charges) on churn

### **6\. 📉 Data Visualization**

* Created impactful visualizations using **Seaborn** and **Matplotlib**:

  * `countplot`, `barplot`, `histplot`, `boxplot`

  * Stacked bar charts and side-by-side comparisons

* Used `FacetGrid` and subplots for multi-feature comparison

### **7\. 🧾 Business Insights & Summary**

* Summarized findings and their implications for customer retention

* Proposed data-backed strategies to reduce churn and improve loyalty

---

## **🔗 Key Deliverables**

* 📘 **Executive Summary**: Insightful report highlighting outcomes and trends

* 📊 **Jupyter Notebook**: Interactive code and visualizations

* 📁 **Dataset**: Customer churn data with demographics and service details

---

## **👨‍🎓 Author**

**Ram Gawande**  
Artifical intelligence and Data science  *Student*  
 Specializing in Exploratory Data Analysis, Visualization, and Machine Learning

