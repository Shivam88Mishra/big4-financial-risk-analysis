# big4-financial-risk-analysis
Exploratory Data Analysis of Big 4 audit firms’ financial risk, compliance violations, fraud detection, and the role of AI in auditing.

# Big 4 Financial Risk & Compliance Analysis

## 📌 Overview
This project performs an Exploratory Data Analysis (EDA) on audit and compliance data from the Big 4 accounting firms (PwC, Deloitte, EY, KPMG).  
The goal is to identify risk patterns, fraud detection trends, and evaluate the impact of AI adoption on audit effectiveness and client satisfaction.  

---

##  Dataset
- **File:** `big4_financial_risk_compliance.csv`
- **Rows:** 100
- **Columns:** 12
- **Key Features:**
  - `Firm_Name` → Audit firm (PwC, Deloitte, EY, KPMG)  
  - `Year` → Audit year  
  - `High_Risk_Cases`, `Fraud_Cases_Detected`, `Compliance_Violations`  
  - `AI_Used_for_Auditing` → Yes/No  
  - `Audit_Effectiveness_Score`  
  - `Client_Satisfaction_Score`  
  - `Total_Revenue_Impact`  

---

##  Analysis Goals
- Compare **audit performance** across firms  
- Identify industries with the **highest compliance risks**  
- Analyze **fraud detection patterns**  
- Evaluate the role of **AI in auditing**  
- Study **client satisfaction vs audit effectiveness**  
- Explore **correlation between revenue impact and risk factors**  

---

##  Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## Project Structure

big4-financial-risk-analysis/
│── data/
│   └── big4_financial_risk_compliance.csv
│── notebooks/
│   └── eda_notebook.ipynb
│── README.md
│── requirements.txt

