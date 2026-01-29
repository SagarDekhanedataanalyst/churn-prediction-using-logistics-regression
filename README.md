# 📊 Customer Churn Prediction using Logistic Regression

## 🧩 Business Problem
Customer churn is a major issue for subscription-based businesses such as telecom and digital service providers. When customers leave, companies lose recurring revenue and must spend significantly more to acquire new customers.

The challenge is that businesses often do not know **which customers are likely to churn** until after they have already left. This leads to untargeted marketing efforts and inefficient retention strategies.

## 🎯 Project Objective
The goal of this project is to build a **machine learning model (Logistic Regression)** that predicts whether a customer is likely to churn, and to identify key factors contributing to churn so the business can take proactive action.

---

## 📁 Dataset
The dataset contains customer information such as:
- Demographics
- Account details (tenure, contract type)
- Billing information (monthly & total charges)
- Service usage

The target variable is **Churn** (Yes/No).

---

## ⚙️ Steps Performed
1. Data loading and cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature encoding and preprocessing  
4. Model building using **Logistic Regression**  
5. Model evaluation using classification metrics  

---

## 🤖 Model Used
**Logistic Regression** was used because:
- It performs well for binary classification problems
- It is interpretable, allowing us to understand drivers of churn

---

## 📊 Model Evaluation
The model was evaluated using:
- Accuracy  
- Confusion Matrix  
- Precision & Recall  

These metrics help measure how well the model identifies customers who are likely to churn.

---

## 🔍 Key Insights
- Customers with shorter tenure are more likely to churn  
- Customers on month-to-month contracts have higher churn risk  
- Higher monthly charges may increase the probability of churn  

---

## 💡 Business Recommendations

1. **Target High-Risk Customers**  
   Use churn probability scores to offer discounts or retention plans to customers likely to leave.

2. **Encourage Long-Term Contracts**  
   Provide incentives for customers to switch from month-to-month to annual plans.

3. **Improve New Customer Onboarding**  
   Engage customers early with support and tutorials to reduce early churn.

4. **Enhance Service Adoption**  
   Encourage customers to use additional services to increase engagement and loyalty.

---

## 🚀 Business Impact
This model helps the company:
- Reduce customer churn  
- Improve customer lifetime value  
- Make data-driven retention decisions  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---


