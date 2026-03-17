# 📊 Paisabazaar Fraud Detection & Credit Risk Analysis

## 📌 Project Overview
Paisabazaar is a leading financial marketplace that helps users apply for loans and credit cards. This project focuses on analyzing customer financial behavior to identify fraud risks and payment defaults, especially customers who fail to pay credit card bills.

The goal is to assist businesses in making better lending decisions and reducing financial losses.

---

## 🎯 Business Objective
- Identify customers who are likely to default on credit card payments  
- Detect potential fraudulent behavior patterns  
- Analyze customer repayment habits  
- Improve risk assessment strategy  

---

## ⚠️ Problem Statement
Financial fraud in lending platforms includes:

- Fake loan applications  
- Identity theft  
- Data misuse  
- Phishing & social engineering  
- Account takeovers  
- Suspicious or inconsistent applications  

This project aims to detect high-risk customers and minimize fraud exposure.

---

## 🗂️ Dataset Description
The dataset contains customer financial and behavioral information such as:

- Age  
- Occupation  
- Annual Income  
- Monthly Salary  
- Number of Bank Accounts  
- Credit Cards  
- Loans  
- Payment delays  
- Outstanding debt  
- Credit utilization  
- Investment behavior  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  

---

## 🧹 Data Cleaning & Feature Engineering

### Data Cleaning
- Removed unnecessary columns (`ID`, `Name`, `SSN`)  
- Handled missing values  
- Removed unrealistic values (age > 100, negative salary)  

### Feature Engineering
- **Debt-to-Income Ratio**
- **Savings Rate**

---

## 📊 Exploratory Data Analysis (EDA)

Followed **UBM Framework**:
- Univariate Analysis  
- Bivariate Analysis  
- Multivariate Analysis  

✔️ Created 20+ visualizations including:
- Credit Score vs Debt Ratio  
- Occupation vs Delayed Payments  
- Monthly Balance Analysis  
- Correlation Heatmap  

---

## 🔍 Key Insights

- High Debt-to-Income Ratio leads to higher delayed payments  
- Some occupations show higher default risk  
- Low savings indicate financial instability  
- Credit score alone is not sufficient to detect fraud  
- Even customers with good credit scores may be financially stressed  

---

## 💡 Business Recommendations

- Use multi-factor risk analysis instead of relying only on credit score  
- Monitor customers with:
  - High debt ratio  
  - Low savings  
  - Frequent delayed payments  
- Apply stricter verification for high-risk customers  
- Provide financial awareness and budgeting guidance  

---

## 📈 Business Impact

- Helps reduce loan defaults  
- Improves fraud detection  
- Enhances credit decision-making  
- Increases overall profitability  

---

## 🚀 Future Improvements

- Build a Machine Learning model for fraud prediction  
- Deploy using Streamlit or Flask  
- Create real-time fraud detection system  
- Develop an interactive dashboard  

---
