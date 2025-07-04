# **📁 Telecom Customer Churn Analysis**

**Author**: Ram gawande  
 **Project**: Customer Retention Analysis using EDA  
 **Tooling**: Python, Pandas, Seaborn, Matplotlib  
 **Date**: June 2025

---

## **📄 File Overview**

* **Notebook Name**: `telecome_data_analysis.ipynb`

* **Dataset**: 7043 customer records with 21 attributes

* **Source**: Telco Customer Churn Dataset

* **Goal**: To identify key factors contributing to customer churn and extract actionable business insights using exploratory data analysis (EDA)

---

## **🧾 Executive Summary**

This project aims to analyze customer churn behavior in a telecom company by using a dataset containing service usage patterns, contract types, demographics, and billing information. The main objective is to identify factors that significantly influence customer churn so that the company can improve retention strategies.

---

## **📌 Key Outcomes**

* 📉 **Overall Churn Rate**: Approximately **26.5%** of customers have churned.

* 🧑‍🤝‍🧑 **Gender**: Churn rate is similar for **Male (27%)** and **Female (26%)** customers.

* 🎯 **Senior Citizens**: Higher churn rate (**42%**) vs non-seniors (**24%**).

* 📶 **Internet Service**:

  * **Fiber Optic**: highest churn rate (**41%**)

  * **DSL**: lower churn (**19%**)

* 🤝 **Contract Type**:

  * **Month-to-month**: churn rate (**43%**)

  * **One-year and Two-year**: significantly lower churn (**11% and 3%**)

* 💳 **Payment Method**:

  * **Electronic Check**: highest churn (**45%**)

  * **Auto bank/credit card**: lowest churn (**15–20%**)

* 🧾 **Monthly Charges**:

  * Customers paying **\> $70/month** churn more.

  * Lower charges \= better retention.

* 🔄 **Tenure**:

  * Customers with **\< 12 months** have highest churn.

  * Longer-tenure \= loyal customers.

---

## **📊 Visual Analysis Highlights**

* 📉 **Churn Distribution** (`countplot`): Shows class imbalance — 26.5% churn rate.

* ⚖️ **Gender vs Churn** (`countplot`): Minimal churn difference between genders.

* 📶 **InternetService vs Churn**: Fiber users churn more than DSL.

* 📊 **Contract Type vs Churn**: Month-to-month has the highest churn.

* 🧮 **Tenure Histogram**: Retention increases significantly after 12 months.

* 💰 **MonthlyCharges Boxplot**: High-paying customers churn more frequently.

---

## **✅ Key Takeaways**

* Customers on **monthly contracts**, **with high bills**, or **using fiber optic services** are more likely to churn.

* **Senior citizens** represent a vulnerable segment with elevated churn risk.

* **Electronic check payments** correlate with higher churn — suggesting possible trust or financial concerns.

* Loyalty improves significantly with **contract length and tenure**.

* **Gender** has **no significant influence** on churn.

---

## **🔍 Business Insights**

* Encourage **annual or two-year contracts** via discount or loyalty incentives.

* Design **retention programs** targeting **senior citizens**.

* Offer **DSL or optimized bundles** for price-sensitive customers.

* Reduce churn among **high-paying customers** with **premium support or rewards**.

* Implement **onboarding journeys and early engagement** to support new customers in the first 12 months.

---

## **🧠 Final Recommendations**

1. **Revamp contract structures** to reward long-term commitments.

2. **Launch an early retention program** for customers in their first year.

3. **Monitor and support senior citizens** through tailored service plans.

4. **Analyze and address complaints** from fiber optic users.

5. **Redesign digital payment channels** to move customers away from electronic checks.

