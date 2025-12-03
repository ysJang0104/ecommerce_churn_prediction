# ecommerce_churn_prediction

# User Behavior–Driven Churn Prediction & Retention Optimization System

This project analyzes user behavior logs to predict churn, identify high-risk users, and provide actionable retention insights.  
It includes: data preprocessing, feature engineering, churn modeling (LightGBM), SHAP explainability, a KPI dashboard, and an A/B test design.

---

## 🔍 Overview

Modern product teams rely on behavioral analytics to understand why users churn and how to improve engagement.  
This project demonstrates an end-to-end workflow used in real product analytics teams:

- Processed 7M+ raw events  
- Built a churn prediction model using behavioral features  
- Explained key churn-driving factors using SHAP  
- Created a product KPI dashboard (Retention, Funnel, Churn Rate)  
- Designed an A/B test scenario for retention improvement  


---

## 🧬 Dataset

**E-Commerce Behavior Data (Kaggle)**  
A large-scale collection of user event logs with features such as:

- user_id  
- event_time  
- event_type (view/cart/purchase)  
- product_id  
- category_id  
- device_type  
- location  

Dataset link: https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store

---

## 🛠 Project Pipeline

Raw Logs → ETL → Feature Engineering → Churn Labeling
→ LightGBM Model → SHAP → KPI Dashboard → A/B Test
