# 📊 Customer Churn Analysis & Prediction

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?logo=powerbi)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 🚀 Project Overview

This project focuses on analyzing customer churn behavior and building predictive models to identify customers at risk of leaving. The goal is to provide **data-driven insights** and help businesses take proactive actions to improve customer retention.

The project follows a complete workflow including:
- Data cleaning  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Machine learning modeling  
- Power BI dashboard visualization  

---

## 🎯 Business Problem

Customer churn directly impacts revenue and growth. Identifying customers who are likely to churn helps businesses:

- Reduce customer loss  
- Improve retention strategies  
- Increase customer lifetime value  

---

## 📁 Project Structure

```
CHURN_PREDICTION/
│
├── data_sets/
│   ├── raw/
│   │   ├── Telco-Customer-Churn.csv
│   │   └── archive.zip
│   │
│   └── processed/
│       └── Prepared.csv
│
├── Data_Acquisition_Preparation.ipynb
├── churn_model.ipynb
├── README.md
```

---

## 📊 Dataset

- Source: Telco Customer Churn Dataset (Kaggle)  
- Records: ~7000 customers  
- Target Variable: **Churn (0 = No, 1 = Yes)**  

### Features include:
- Customer demographics  
- Account details (tenure, contract)  
- Billing information  
- Services subscribed  

---

## ⚙️ Data Processing

- Handled missing and inconsistent values  
- Converted categorical features into numerical  
- Created new features:
  - Tenure Groups (New, Mid, Loyal)  
  - Monthly Charges Groups  
  - Total Services Count  
  - Average Monthly Spend  

---

## 📈 Exploratory Data Analysis (EDA)

### Key Insights:

- Customers with **low tenure** are more likely to churn  
- **Higher monthly charges** increase churn probability  
- **Month-to-month contracts** have the highest churn  
- Customers with fewer services tend to churn more  

---

## 🤖 Machine Learning Models

Models used:
- Logistic Regression  
- Random Forest  
- Gradient Boosting  

### 🔍 Performance

| Model | Accuracy |
|------|--------|
| Logistic Regression | ~79% |
| Random Forest | ~79% |
| Gradient Boosting | ~80% (Best) |

---

## ⚡ Model Optimization

- Cross Validation (CV)  
- Hyperparameter tuning (GridSearchCV)  
- Feature selection  

Result: Only minor improvement (~1%), indicating the dataset is already well-structured.

---

## 📊 Power BI Dashboard

An interactive dashboard was designed to visualize churn insights.

---

### 📌 Dashboard Overview Page
![Dashboard Overview](images/dashboard_overview.png)

---

### 📌 Churn Analysis Page
![Churn Analysis](images/churn_analysis.png)

---

### 📌 Customer Risk Segmentation
![Customer Segmentation](images/customer_segmentation.png)

---

## 🎯 Key Dashboard Insights

- Month-to-month customers have highest churn  
- High-paying customers are more likely to leave  
- New customers are at higher risk  
- More services reduce churn probability  

---

## 💼 Business Recommendations

- Encourage long-term contracts with incentives  
- Offer discounts for high-paying customers  
- Improve onboarding experience for new users  
- Promote bundled services  

---

## 🧠 Key Learnings

- Importance of feature engineering  
- Model interpretability vs complexity  
- End-to-end data analytics workflow  
- Translating data into business insights  

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy)  
- Scikit-learn  
- Matplotlib, Seaborn  
- Power BI  
- Jupyter Notebook  

---

## 🔗 Future Improvements

- Deploy model using Flask API  
- Use advanced models (XGBoost, LightGBM)  
- Real-time prediction system  
- Improve dashboard interactivity  

---

## 📌 Conclusion

This project demonstrates how data analytics and machine learning can be used to predict churn and support business decision-making.