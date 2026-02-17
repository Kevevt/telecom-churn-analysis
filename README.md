# Telecom Churn Analysis: Data-Driven Retention Strategy
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-444876?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

## 📋 Executive Summary
This project delivers a comprehensive Exploratory Data Analysis (EDA) and predictive modeling assessment for a telecommunications provider. The goal was to diagnose the root causes of a **26.5% global churn rate** and provide actionable, data-backed recommendations to improve customer retention.

> **Context:** Developed as part of the **Oracle Next Education (ONE)** specialization in Data Science & Analytics.

---

## 🔍 Key Strategic Insights

### 📉 The "6-Month Cliff"
Analysis of customer tenure reveals a critical drop-off point. **Fiber Optic** users exhibit the highest churn probability within their **first 6 months** of service.
* **Strategic Action:** Implement a "VIP Onboarding" program during the first semester to mitigate early-stage friction.

### 🧬 Contractual DNA
Statistical correlation (**-0.40**) confirms that contract duration is the strongest predictor of retention.
* **Observation:** "Month-to-month" contracts act as the primary leak in the revenue stream, while 1-year and 2-year contracts show near-zero churn.

### 🌳 The "Churn Profile" (Decision Tree)
Using a Decision Tree Classifier, we mapped the specific profile of a high-risk customer:
1.  **Contract:** Month-to-Month
2.  **Internet Service:** Fiber Optic
3.  **Payment Method:** Electronic Check

---

## 🛠️ Technical Workflow
This project simulates a real-world data analysis task, focusing on data quality and interpretability:

* **Data Wrangling:** Transformed raw JSON/CSV data, handling missing values and encoding categorical features (e.g., converting 'Yes/No' text to binary integers) for machine learning compatibility.
* **Statistical Analysis:** Generated Correlation Matrices to filter out noise and identify variables with true predictive power.
* **Visual Storytelling:** Utilized **Waffle Charts** and **Density Plots** to communicate complex patterns to non-technical stakeholders effectively.

---

## 👤 About the Author
**Kevin Mendoza**
* 🧪 **Biotechnology Engineer** leveraging scientific rigor in Data Analytics.
* ⚙️ **Aspiring Data Engineer:** Currently focused on mastering Python, SQL, and Data Pipelines to build scalable data infrastructure.
