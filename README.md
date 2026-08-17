# 🔮 Customer Churn Prediction System

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-red.svg)](https://streamlit.io)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3+-orange.svg)](https://scikit-learn.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A production-ready **machine learning application** that predicts customer churn probability using classification models and provides actionable retention insights through an interactive Streamlit dashboard.

🔗 **[Live Demo](https://customer-churn-prediction-by-na.streamlit.app/)**

---

## 🎯 Overview

Customer Churn Prediction helps businesses identify customers who are likely to leave and take proactive retention actions.

The application provides an end-to-end workflow to:

- 🔮 Predict individual customer churn probability
- 📊 Process multiple customers through batch prediction
- ⚠️ Segment customers by churn risk
- 🔍 Identify important churn drivers
- 💡 Generate targeted retention recommendations
- 📈 Visualize model performance and business insights

---

## ✨ Key Features

### 🔮 Single Customer Prediction

- Real-time churn probability
- Interactive risk gauge
- Low / Medium / High risk classification
- Personalized retention recommendations
- Feature-based risk analysis

### 📊 Batch Prediction

- Upload customer data through CSV
- Automatic data processing
- Churn probability for every customer
- Risk segmentation
- Downloadable prediction results
- Interactive analytics

### 📈 Model Insights

- Accuracy, Precision, Recall, F1, and AUC-ROC
- Confusion matrix
- Feature importance
- Business-focused model interpretation

### 💡 Retention Recommendations

The system generates recommendations based on customer characteristics such as:

- Tenure
- Monthly charges
- Age
- Customer risk level

---

## 🖥️ Application Flow

```text
Customer Data
      │
      ▼
Data Preprocessing
      │
      ▼
ML Classification Model
      │
      ▼
Churn Probability
      │
      ├───────────────┐
      ▼               ▼
 Risk Level      Key Risk Factors
      │               │
      └───────┬───────┘
              ▼
     Retention Recommendation
