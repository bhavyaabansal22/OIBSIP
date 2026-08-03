<h1 align="center">
💳 Fraud Transaction Detection
</h1>

<p align="center">
Machine Learning Pipeline for Detecting Fraudulent Financial Transactions
</p>

<p align="center">

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=22&pause=1000&color=2563EB&center=true&vCenter=true&width=700&lines=Imbalanced+Classification;SMOTE+Oversampling;Logistic+Regression+%7C+Random+Forest;Precision+%7C+Recall+%7C+ROC-AUC"/>

</p>

---

<p align="center">

<!-- <img src="YOUR-FRAUD-DETECTION-GIF-LINK-HERE" width="700"> -->

</p>

---

## 📌 Project Overview

Financial fraud detection is one of the most important applications of Machine Learning in the banking and fintech industries.

Since fraudulent transactions make up only **1.51%** of all transactions, traditional classification models struggle to identify fraud effectively.

This project develops a complete **Machine Learning Pipeline** capable of detecting fraudulent financial transactions while addressing severe class imbalance using **SMOTE (Synthetic Minority Oversampling Technique).**

Two machine learning models were compared:

- 📈 Logistic Regression
- 🌳 Random Forest Classifier

using industry-standard evaluation metrics such as Precision, Recall, F1-Score and ROC-AUC.

---

# 🚀 Tech Stack

<p align="center">

<img src="https://skillicons.dev/icons?i=python" height="55">
<img src="https://cdn.simpleicons.org/pandas/150458" height="55">
<img src="https://cdn.simpleicons.org/numpy/013243" height="55">
<img src="https://cdn.simpleicons.org/scikitlearn/F7931E" height="55">
<img src="https://cdn.simpleicons.org/jupyter/F37626" height="55">

</p>

---

# 🎯 Objectives

✔ Detect fraudulent transactions

✔ Handle severe class imbalance

✔ Apply SMOTE oversampling

✔ Compare Logistic Regression & Random Forest

✔ Evaluate using Precision, Recall, F1-Score & ROC-AUC

✔ Analyze feature importance

✔ Discuss real-world scalability

---

# 📊 Dataset Summary

| Item | Value |
|------|------:|
| Total Transactions | 10,000 |
| Legitimate Transactions | 9,849 |
| Fraudulent Transactions | 151 |
| Fraud Rate | **1.51%** |

---

# ⚡ Machine Learning Workflow

```text
Financial Transactions
          │
          ▼
 Data Cleaning & EDA
          │
          ▼
 Feature Engineering
          │
          ▼
 Train-Test Split
 (Stratified)
          │
          ▼
 One-Hot Encoding
          │
          ▼
      SMOTE
          │
          ▼
 Model Training
    ┌─────────────┐
    │             │
    ▼             ▼
 Logistic     Random Forest
 Regression
    │             │
    └──────┬──────┘
           ▼
   Model Evaluation
           │
           ▼
 Feature Importance
```

---

# 📈 Exploratory Data Analysis

The project includes:

📌 Class imbalance visualization

📌 Transaction amount comparison

📌 Fraud vs Non-Fraud distribution

📌 Time-of-day fraud analysis

📌 Correlation analysis

📌 Feature relationship analysis

---

# 🤖 Models Used

| Model | Purpose |
|--------|---------|
| Logistic Regression | Baseline linear classifier |
| Random Forest | Ensemble learning classifier |

---

# 📊 Model Performance

| Metric | Logistic Regression | Random Forest |
|---------|-------------------:|--------------:|
| Accuracy | 97% | **99%** |
| Precision | 30% | **94%** |
| Recall | **93%** | 57% |
| F1 Score | 46% | **71%** |

---

# 🎯 Key Insights

🟢 Logistic Regression

- Excellent Recall
- Detects most fraud cases
- Higher False Positives

---

🟢 Random Forest

- Excellent Precision
- Better F1 Score
- Fewer False Positives
- Better overall balance

---

# 📉 Why Accuracy Isn't Enough?

Because only **1.51%** of transactions are fraudulent,

a model predicting **every transaction as legitimate** would still achieve nearly **98.5% Accuracy** while completely failing its actual purpose.

Therefore this project focuses on

- Precision
- Recall
- F1-Score
- ROC-AUC

instead of Accuracy alone.

---

# 🔍 Feature Importance

The trained models were analyzed to identify the most influential features contributing to fraud prediction.

Feature importance provides:

- Better model interpretability
- Business insights
- Fraud pattern understanding
- Explainable machine learning

---

# 🌍 Real-World Scalability

To process **1 Million+ transactions per hour**, this pipeline can be extended using:

- Apache Kafka
- Apache Spark
- Cloud Deployment
- REST APIs
- Batch + Stream Processing
- Continuous Monitoring

---

# 💡 Key Learnings

✅ Handling Imbalanced Data

✅ SMOTE Oversampling

✅ Machine Learning Pipelines

✅ One-Hot Encoding

✅ Logistic Regression

✅ Random Forest

✅ ROC-AUC Analysis

✅ Precision–Recall Trade-off

✅ Feature Importance

---

# 🔮 Future Improvements

- XGBoost
- LightGBM
- Threshold Optimization
- Explainable AI (SHAP)
- Real-Time Fraud Detection Dashboard
- Hyperparameter Tuning

---

# 👨‍💻 Author

### **Bhavyaa Bansal**

**Data Analytics Intern**

**Oasis Infobyte**

---

<p align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,100:7F5AF0&height=120&section=footer"/>

</p>
