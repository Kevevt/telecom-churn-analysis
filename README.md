# Telecom X Latam: Customer Churn Analysis
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-444876?style=for-the-badge&logo=python&logoColor=white)

## 📋 Executive Summary
This project delivers an end-to-end **Exploratory Data Analysis (EDA)** and predictive assessment for a telecommunications provider. By analyzing behavior patterns, I diagnosed the root causes of a **26.5% global churn rate** and developed data-driven strategies to recover potential revenue losses.

> **Context:** Developed as part of the **Oracle Next Education (ONE)** specialization in Data Science & Analytics.

---
## 📂 Project Structure

```text
challenge2-data-science-LATAM/
│
├── images/                      # Exported visualizations for documentation
│   ├── decision_tree.png
│   ├── feature_importance.png
│   ├── global_churn.png
│   └── tenure_churn.png
├── README.md                    # Project documentation and insights
├── TelecomX_Data.json           # Raw dataset
├── TelecomX_diccionario.md      # Data dictionary/metadata
└── TelecomX_LATAM.ipynb         # Main Jupyter Notebook with full EDA and modeling
```
---


## 🔍 Key Strategic Findings

### 1. The "Critical Semester" (~42% of Total Churn) 📉
Tenure analysis reveals a massive drop-off early in the customer lifecycle. **41.9% of all historical churn (783 out of 1,869 lost customers)** occurs within the **first 6 months** of service.
* **Insight:** If a customer survives the first semester, the retention probability stabilizes as the churn curve flattens.
* **Strategy:** Implement a "First 180 Days" VIP onboarding and loyalty program for new users.

### 2. Contract Stability 📄
Statistical analysis confirms that **Month-to-Month** contracts are the primary volatility factor. Transitioning users to 1-year plans drastically reduces exit probability.

### 3. The "Churn Profile" (Decision Tree) 🌳
Using a Decision Tree Classifier, we mapped the specific high-risk profile:
`Month-to-Month Contract` + `Fiber Optic` + `Electronic Check Payment`.

---

## 📊 Visual Analysis Gallery

### 1. The Scale of the Problem

<div align="center">
  <img src="images/global_churn.png" width="380">
</div>

> **Insight:** We are currently losing **1 in 4 customers** (~26.5%). In absolute volume, out of a base of 7,043 clients, **1,869 have canceled** their service. This visualizes the immediate impact on revenue stability.

---

### 2. The "6-Month Cliff" (Critical Insight)
<div align="center">
  <img src="images/tenure_churn.png" width="820">
</div>

> **Insight:** The red dotted line marks the danger zone. **41.9% of all churn events (783 customers)** happen within the first half-year. If we retain a user past month 6, their lifetime value and stability increase significantly.

---

### 3. What Drives the Exit? (Mathematical Proof)
<div align="center">
  <img src="images/feature_importance.png" width="820">
</div>

> **Insight:** Unlike common intuition, demographics (Gender, Partner) matter very little. The **Contract Type** and **Internet Service** technical specs are the true drivers of dissatisfaction.

---

### 4. The Path to Churn (Decision Rules)
<div align="center">
  <img src="images/decision_tree.png" width="820">
</div>

> **Insight:** A specific "Toxic Combo" was identified: Customers with a **Month-to-Month contract**, using **Fiber Optic**, and paying via **Electronic Check** have the highest probability of leaving.

---

## 🛠️ Technical Workflow
This project simulates a real-world Data Analysis task:
1.  **ETL & Cleaning:** Transformed raw JSON data, handled missing values, and encoded categorical features for ML compatibility.
2.  **Feature Engineering:** Validated variable importance using Correlation Matrices and Random Forest feature ranking.
3.  **Modeling:** Implemented a Decision Tree Classifier to extract human-readable business rules for the marketing team.

---

## 👤 About the Author
**Kevin Mendoza**
* 🧪 **Biotechnology Engineer** 
* ⚙️ **Data Engineer in Training:** Transitioning into scalable data infrastructure.
