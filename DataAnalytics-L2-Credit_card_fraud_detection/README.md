# 💳 Fraud Transaction Detection using Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Imbalanced-Learn](https://img.shields.io/badge/Imbalanced--Learn-SMOTE-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</p>

---

## 📖 Project Overview

Financial fraud detection is one of the most critical applications of machine learning in the banking and fintech industries. Since fraudulent transactions account for only a tiny fraction of all transactions, the problem becomes a **highly imbalanced binary classification task**.

This project builds a complete **machine learning pipeline** to identify fraudulent financial transactions while addressing class imbalance using **SMOTE (Synthetic Minority Oversampling Technique)**.

Two classification models—**Logistic Regression** and **Random Forest Classifier**—were trained and evaluated using industry-recommended metrics such as **Precision, Recall, F1-Score, and ROC-AUC**.

---

# 🎯 Objectives

- Detect fraudulent financial transactions using Machine Learning.
- Understand and analyze severe class imbalance.
- Handle minority-class imbalance using **SMOTE**.
- Compare multiple classification algorithms.
- Evaluate models using appropriate metrics instead of relying only on Accuracy.
- Interpret important features influencing fraud detection.
- Discuss scalability for real-world banking systems.

---

# 📂 Dataset Information

The dataset consists of **10,000 financial transactions** with the following features:

| Feature | Description |
|----------|-------------|
| transaction_id | Unique transaction ID |
| amount | Transaction amount |
| transaction_hour | Hour when transaction occurred |
| merchant_category | Merchant category |
| foreign_transaction | Whether transaction was international |
| location_mismatch | Customer location mismatch |
| device_trust_score | Trust score of user's device |
| velocity_last_24h | Number of recent transactions |
| cardholder_age | Customer age |
| is_fraud | Target Variable |

---

# 📊 Dataset Summary

| Metric | Value |
|---------|------:|
| Total Transactions | 10,000 |
| Legitimate Transactions | 9,849 |
| Fraudulent Transactions | 151 |
| Fraud Percentage | **1.51%** |

> **Observation:** The dataset is highly imbalanced, making fraud detection significantly more challenging than a standard classification problem.

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

---

# 📈 Exploratory Data Analysis

The following analyses were performed:

- ✅ Class distribution analysis
- ✅ Fraud percentage calculation
- ✅ Distribution of transaction amounts
- ✅ Fraud vs Non-Fraud comparison
- ✅ Transaction hour analysis
- ✅ Correlation analysis
- ✅ Feature distribution visualization

---

# ⚙️ Machine Learning Pipeline

```
                 Raw Dataset
                      │
                      ▼
              Data Preprocessing
                      │
       ┌──────────────┴──────────────┐
       │                             │
 One-Hot Encoding            Missing Value Handling
       │                             │
       └──────────────┬──────────────┘
                      ▼
              Train-Test Split
           (Stratified Sampling)
                      │
                      ▼
                   SMOTE
     (Training Set Only - Balancing)
                      │
                      ▼
            Model Training
      ┌────────────────────────┐
      │                        │
      ▼                        ▼
Logistic Regression     Random Forest
      │                        │
      └──────────────┬─────────┘
                     ▼
          Model Evaluation
                     │
                     ▼
        Feature Importance Analysis
```

---

# 🤖 Models Implemented

### 1️⃣ Logistic Regression

A linear classification algorithm used as the baseline model for fraud detection.

### 2️⃣ Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to improve prediction performance.

---

# 📊 Model Performance

| Metric | Logistic Regression | Random Forest |
|---------|-------------------:|--------------:|
| Accuracy | 97% | **99%** |
| Precision | 30% | **94%** |
| Recall | **93%** | 57% |
| F1-Score | 46% | **71%** |

---

# 📈 Key Findings

### Logistic Regression

- Very high Recall (93%)
- Successfully detected most fraud cases
- Generated more false positives
- Suitable when missing fraud is costly

### Random Forest

- Excellent Precision (94%)
- Highest overall F1-Score
- Produced fewer false alarms
- Better balance between fraud detection and customer convenience

---

# 📉 Why Accuracy is Misleading?

With only **1.51% fraudulent transactions**, a model that predicts every transaction as **Non-Fraud** would still achieve approximately **98.5% Accuracy** while completely failing to detect fraud.

Therefore, the following metrics were used instead:

- Precision
- Recall
- F1-Score
- ROC-AUC Score

These metrics provide a much more reliable assessment of fraud detection performance.

---

# 📌 ROC-AUC Analysis

The models achieved an excellent ROC-AUC score, indicating a strong ability to distinguish fraudulent transactions from legitimate ones across different classification thresholds.

ROC-AUC is particularly useful for evaluating imbalanced datasets because it measures ranking performance rather than relying on a single prediction threshold.

---

# 🔍 Feature Importance

Feature importance analysis was performed to identify the variables that contributed most to fraud prediction.

This helps:

- Improve model interpretability
- Understand fraud patterns
- Support business decision-making
- Identify key fraud indicators

---

# 🚀 Scalability Discussion

To process **millions of transactions per hour**, this solution could be extended using:

- Apache Kafka for real-time data streaming
- Apache Spark for distributed processing
- Distributed Machine Learning
- REST APIs for deployment
- Cloud-based infrastructure
- Continuous model monitoring and retraining

---

# 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Handling Imbalanced Datasets
- One-Hot Encoding
- SMOTE Oversampling
- Machine Learning Pipelines
- Logistic Regression
- Random Forest
- Model Evaluation
- ROC-AUC Analysis
- Feature Importance
- Business Interpretation of ML Results

---

# 🔮 Future Improvements

- XGBoost & LightGBM
- Hyperparameter Tuning
- Threshold Optimization
- Cost-Sensitive Learning
- Explainable AI (SHAP & LIME)
- Real-Time Fraud Detection Dashboard
- Deep Learning-based Fraud Detection

---

# 📝 Conclusion

This project successfully demonstrated how machine learning can be used to detect fraudulent financial transactions despite severe class imbalance.

Using **SMOTE** significantly improved the model's ability to learn fraud patterns, while appropriate evaluation metrics such as **Precision, Recall, F1-Score, and ROC-AUC** provided a more meaningful assessment than Accuracy alone.

Logistic Regression prioritized detecting almost all fraudulent transactions through a high Recall, whereas Random Forest achieved a stronger balance between detecting fraud and minimizing false alarms through higher Precision and F1-Score.

Overall, the project provided valuable experience in preprocessing imbalanced datasets, building end-to-end machine learning pipelines, evaluating classification models, and understanding the practical challenges involved in real-world fraud detection systems.

---

## 👨‍💻 Author

**Bhavyaa Bansal**

**Data Analytics Intern**

**Oasis Infobyte**

---
⭐ *If you found this project helpful, consider giving it a star!*