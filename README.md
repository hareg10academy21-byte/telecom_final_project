# Telecom Customer Churn Prediction Using Machine Learning

## Project Overview

Customer churn is one of the most significant challenges faced by telecommunications companies. Losing existing customers reduces revenue and increases customer acquisition costs. This project develops a machine learning solution capable of predicting customers who are likely to churn, allowing businesses to implement proactive retention strategies.

Using historical customer behavior and service usage data, a Random Forest classifier was trained to identify high-risk customers and provide business recommendations that support customer retention and revenue protection.

This project was completed as part of the **GCI World AI & Machine Learning Program**.

---

# Business Problem

Telecommunication companies invest significant resources in acquiring new customers. However, retaining existing customers is generally more cost-effective than acquiring new ones.

Without an accurate prediction system, companies often identify churn only after customers have already left.

The objective of this project is to:

- Predict customer churn using machine learning.
- Identify the most influential factors driving churn.
- Recommend business strategies to reduce customer loss.
- Estimate the financial impact of targeted retention campaigns.

---

# Dataset

The project uses a telecommunications customer dataset containing demographic information, account history, service usage, billing details, and customer behavior.

The dataset includes variables such as:

- Monthly Revenue
- Monthly Minutes of Use
- Device Age
- Device Type
- Contract Information
- Service Usage
- Customer Tenure
- Billing Information
- Churn Status (Target Variable)

---

# Project Workflow

The project follows the complete machine learning lifecycle:

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Feature Engineering
5. Model Development
6. Model Evaluation
7. Business Impact Analysis
8. Executive Recommendations

---

# Exploratory Data Analysis

Several visualizations were created to better understand customer behavior, including:

- Customer Churn Distribution
- Monthly Revenue Distribution
- Monthly Usage Distribution
- Correlation Heatmap
- Average Revenue by Churn Status
- Average Usage by Churn Status

These analyses provided valuable insights into customer behavior before model development.

---

# Machine Learning Model

The project uses the **Random Forest Classifier** because of its strong predictive performance and ability to rank feature importance.

Model development included:

- Train/Test Split
- Feature Scaling (where appropriate)
- Random Forest Training
- Prediction
- Performance Evaluation

---

# Model Evaluation

The model was evaluated using multiple performance metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- Feature Importance

These evaluation techniques provide a comprehensive assessment of model performance.

---

# Business Insights

The analysis revealed several important business findings:

- Customers using older mobile devices are more likely to churn.
- Customers with refurbished devices exhibit higher churn risk.
- Long-term customers benefit from loyalty retention programs.
- Declining monthly usage serves as an early indicator of churn.
- Device quality and customer engagement significantly influence customer retention.

These findings enable businesses to implement proactive customer retention strategies.

---

# Business Impact Analysis

The predictive model identified:

**High-Risk Customers:** **581**

Business assumptions:

- Average Monthly Revenue per Customer: **$58**
- Retention Campaign Cost per Customer: **$10**
- Campaign Success Rate: **25%**

Estimated Business Impact:

- Target only high-risk customers.
- Protect recurring monthly revenue.
- Reduce unnecessary marketing expenses.
- Improve customer lifetime value.
- Increase return on retention investment.

---

# Executive Recommendations

Based on the machine learning results, the following recommendations are proposed:

### 1. Device Upgrade Program

Offer discounted device upgrades for customers using older mobile phones.

### 2. Refurbished Device Campaign

Provide trade-in incentives for customers using refurbished devices.

### 3. Loyalty Reward Program

Introduce loyalty rewards for long-tenure customers to improve retention.

### 4. Usage Monitoring

Monitor customers with declining service usage and trigger personalized offers before churn occurs.

### 5. Personalized Retention Campaigns

Use predicted churn probabilities to prioritize customer retention resources.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Repository Structure

```
Telecom-Churn-Prediction/
│
├── Telecom_Customer_Churn_Prediction.ipynb
├── Telecom_Customer_Churn_Report.pdf
├── README.md
├── requirements.txt
├── figures/
│   ├── churn_distribution.png
│   ├── revenue_distribution.png
│   ├── usage_distribution.png
│   ├── correlation_heatmap.png
│   ├── avg_revenue_churn.png
│   ├── avg_usage_churn.png
│   ├── feature_importance.png
│   ├── confusion_matrix.png
│   └── roc_curve.png
│
└── dataset/
    └── telecom_churn.csv
```

---

# Results

The Random Forest model successfully predicts customer churn while providing interpretable business insights.

The model enables organizations to:

- Identify high-risk customers early.
- Reduce customer churn.
- Improve customer satisfaction.
- Increase revenue retention.
- Support data-driven decision making.

---

# Future Improvements

Future work may include:

- Hyperparameter Optimization
- XGBoost Implementation
- LightGBM Comparison
- SHAP Explainability
- Real-Time Prediction API
- Customer Segmentation
- Deployment using Flask or FastAPI

---

# References

- Breiman, L. (2001). Random Forests. Machine Learning.
- Scikit-learn Documentation
- Pandas Documentation
- Matplotlib Documentation
- Seaborn Documentation

---

# Author

**Haregeweyn Ataklt**

GCI World AI & Machine Learning Program

2026