# 🏦 Bank Churn Analysis

## 📌 Project Overview

Customer churn is a key concern in the banking sector, directly impacting revenue and long-term customer value. This project analyzes customer churn behavior using real banking data and summarizes key factors that influence whether a customer stays or leaves.

The project is structured into two major phases:
1. **Part 1** – Define the business objective and perform univariate analysis.
2. **Part 2** – Conduct bivariate and multivariate analysis to derive insights that support business decisions.

---

## 🎯 Business Objective

The aim is to identify **what differentiates churned customers** from those who stay and interpret how demographic, transactional, and behavioral features affect churn. These insights are expected to:
- Help **retain valuable customers**.
- Design better **engagement strategies**.
- Improve **product offerings** based on customer segments.

---

## 📁 Dataset

- **File**: `S1_BankChurn_Data.csv`
- **Size**: 10,000 records, 14 features
- **Target Variable**: `Attrition_Flag`  
  (`Attrited Customer` or `Existing Customer`)

### Key Features:
- **Demographics**: Age, Gender, Marital Status, Education Level
- **Financials**: Credit Limit, Income Category, Avg_Utilization_Ratio
- **Behavior**: Total_Trans_Ct, Card_Category, Months_Inactive_12_mon, etc.

---

## 🧪 Notebook Summary

### 📓 Part 1: Data Understanding & Univariate Analysis

- Inspected structure, data types, and null values.
- Separated numerical and categorical variables.
- Handled outliers in `Customer_Age` and `Dependent_count`.
- Visualized features like `Attrition_Flag`, `Gender`, `Education_Level`, and more.

✅ **Key Takeaways**:
- 84% of customers are existing; 16% have churned.
- Most customers are graduates, married, and earn less than $40,000.
- Majority use the Blue card.

---

### 📓 Part 2: Bivariate & Multivariate Analysis

- Investigated how `Attrition_Flag` relates to other variables.
- Analyzed churn trends across:
  - **Categorical pairs**: (e.g., Gender × Attrition)
  - **Categorical & continuous pairs**: (e.g., Age × Attrition)
- Plotted heatmaps, bar charts, and box plots to support observations.

🔍 **Key Interpretations**:
- Higher attrition among **female** customers.
- Customers with **lower income** and **fewer dependents** churn more.
- Churners tend to have **low credit utilization** and **low transaction counts**.
- Most churn is from **Blue card** holders.

---

## 📊 Business Insights

- **Retention Focus**:
  - Improve engagement with low-usage customers.
  - Personalize offers for blue card users and low-income earners.

- **Product Strategy**:
  - Introduce more attractive features to prevent churn among at-risk segments.

- **Customer Experience**:
  - Analyze inactivity reasons and provide targeted communication for reactivation.

---

## 🚀 Tech Stack

- **Languages**: Python
- **Tools**: Jupyter Notebook
- **Libraries**: pandas, seaborn, matplotlib, numpy

---


---

## 🙌 Acknowledgements

Thanks to the financial analytics community and open-source contributors for providing techniques and tools used in this project.

---

## 👨‍💻 Author

**Subhadeep Banerjee**  
*Intermediate Python Developer | AI Researcher | Data Enthusiast*

---

## 📢 Note

This project contains **only EDA and interpretation**; no modeling or prediction has been done. Future work may include applying machine learning models to predict churn probability.


