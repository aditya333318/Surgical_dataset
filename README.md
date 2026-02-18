# 🏥 Surgical Complication & Mortality Prediction (Deep Learning)

## 📌 Project Overview

This project focuses on predicting **postoperative complications** and **30-day mortality** using clinical, demographic, and surgical risk factors.

The dataset contains **14,635 patient records** and 25 structured features, making it suitable for machine learning and deep learning classification models.

---

## 📊 Dataset Summary

- **Total Records:** 14,635
- **Total Features:** 25
- **Target Variables:**
  - `complication` (0 = No, 1 = Yes)
  - `mort30` (0 = Survived, 1 = Died within 30 days)
- **Missing Values:** None
- **Problem Type:** Binary Classification

---

## 🧾 Feature Categories

### 👤 Demographics
- Age
- Gender
- Race
- BMI

### 🏥 Baseline Comorbidities
- Cancer
- Cardiovascular disease
- Diabetes
- Dementia
- Digestive conditions
- Osteoarthritis
- Psychiatric conditions
- Pulmonary disease
- Charlson Comorbidity Index

### ⚕️ Surgical Risk Indicators
- ASA Status
- AHRQ Clinical Classification
- Risk-adjusted complication index (RSI)
- Risk-adjusted mortality index (RSI)
- CCS complication & mortality rates

### ⏰ Temporal Features
- Day of week
- Month
- Hour of surgery
- Moon phase

---

## 🎯 Objectives

- Predict postoperative complications
- Predict 30-day mortality
- Build deep learning classification models
- Evaluate model performance using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- TensorFlow / Keras (Deep Learning)

---

## 🚀 Workflow

1. Data Cleaning & Exploration
2. Feature Scaling
3. Train-Test Split
4. Model Building
5. Model Evaluation
6. Performance Optimization

---

## 📌 Key Insights

- Mortality rate is highly imbalanced.
- Complication prediction is more balanced compared to mortality.
- Risk-adjusted indices significantly influence prediction performance.

---



## 📬 Author

Aditya Uttekar  
Aspiring Data Scientist | Machine Learning Enthusiast  

---

## ⭐ If you found this useful

Please consider giving this repository a star!
