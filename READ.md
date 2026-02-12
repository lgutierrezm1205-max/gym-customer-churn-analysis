# 🏋️ Customer Churn Prediction & Segmentation  
### Machine Learning Project | Model Fitness Case Study

## 📌 Project Overview

This project analyzes customer churn for a gym chain (Model Fitness) to identify members at risk of cancellation and develop data-driven retention strategies.

By combining predictive modeling and customer segmentation, this analysis transforms raw customer data into actionable business insights.

---

## 🎯 Business Objectives

- Predict the probability of customer churn for the upcoming month.
- Identify the key drivers influencing customer attrition.
- Segment customers into meaningful behavioral groups.
- Provide strategic recommendations to improve retention and engagement.

---

## 📊 Dataset Description

The dataset includes customer demographics, membership details, behavioral activity, and spending patterns, such as:

- Contract duration and remaining months
- Visit frequency (historical and current month)
- Participation in group classes
- Additional service spending
- Customer lifetime (in months)
- Promotional and partner affiliations
- Churn indicator (target variable)

---

## 🔎 Exploratory Data Analysis (EDA)

A comprehensive exploratory analysis was conducted to:

- Identify missing values and data inconsistencies
- Compare statistical differences between churned and retained customers
- Visualize feature distributions
- Analyze correlations between variables

### Key Insights

- Short-term contracts are strongly associated with higher churn.
- Lower visit frequency is a major indicator of potential cancellation.
- Customers with longer lifetime and higher additional spending show greater loyalty.
- Remaining months in contract is one of the strongest predictive features.

---

## 🤖 Predictive Modeling

Two binary classification models were developed and evaluated:

- Logistic Regression  
- Random Forest Classifier  

### Evaluation Metrics

- Accuracy  
- Precision  
- Recall  

The Random Forest model demonstrated superior performance, particularly in identifying high-risk customers (higher recall), making it more suitable for proactive retention strategies.

---

## 👥 Customer Segmentation

Unsupervised learning techniques were applied to identify customer profiles:

- Hierarchical Clustering (Dendrogram analysis)
- K-Means Clustering (n = 5)

### Segmentation Insights

- Clear behavioral differences exist between loyal and high-risk customers.
- Certain clusters exhibit significantly higher churn rates.
- Engagement level and contract duration heavily influence retention probability.

This segmentation enables targeted marketing and personalized engagement strategies.

---

## 📈 Business Recommendations

Based on predictive and clustering analysis:

1. Encourage short-term members to migrate to longer contract plans.
2. Monitor customers with declining attendance patterns.
3. Develop targeted retention campaigns for high-risk clusters.
4. Increase engagement through group classes and value-added services.

---

## 🛠 Tools & Technologies

- Python  
- Pandas & NumPy  
- Matplotlib  
- Scikit-learn  
- Logistic Regression  
- Random Forest  
- Hierarchical Clustering & K-Means  

---

## 📂 Project Structure

