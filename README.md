# 🚨 Fraud Detection ML Application

A complete end-to-end machine learning project for detecting fraudulent financial transactions, featuring a production-ready Streamlit web app.

This repository demonstrates:
- Data analysis
- Feature engineering
- Model training
- Pipeline building
- Real-time predictions with Streamlit UI
- Clean, modular, maintainable project structure

---

## 📦 1. Project Overview

Financial fraud remains a major challenge in modern digital transactions.  
This project builds a machine learning pipeline to classify whether a transaction is **fraudulent (1)** or **legitimate (0)**.

The application includes:
- A trained ML pipeline (`fraud_detection_pipeline.pkl`)
- A streamlined Streamlit frontend for real-time usage
- Structured notebooks for reproducibility
- Modular code designed for clarity and production-readiness

---

## 📊 3. Dataset Description

*Dataset is not included in the repository to avoid large files.*

Typical features:
- **type** — transaction type  
- **amount** — transaction value  
- **oldbalanceOrg** — sender balance (before)  
- **newbalanceOrig** — sender balance (after)  
- **oldbalanceDest** — receiver balance (before)  
- **newbalanceDest** — receiver balance (after)  
- **isFraud** — target label  

The target variable is **isFraud** (0 = safe, 1 = fraud).

---

## 🧠 4. Machine Learning Pipeline

### 4.1 Preprocessing
- Encoding categorical features  
- Scaling numerical values  
- Handling inconsistent balance values  
- Train-test split  
- Optional: Handling class imbalance  

### 4.2 Models Tested
- Logistic Regression  
- Random Forest  
- Decision Trees  
- XGBoost  
- Gradient Boosting  


