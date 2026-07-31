# 🍷 Wine Quality Classification using Machine Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=for-the-badge&logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

## 📌 Project Overview

Wine quality is influenced by several physicochemical properties such as acidity, sugar content, sulphates, alcohol concentration, density, and pH.

This project develops machine learning models capable of classifying wines into **Good** and **Bad** quality categories using these chemical characteristics. Three classification algorithms were trained and compared to determine the most suitable model for deployment.

---

## 🎯 Objective

The objective of this project is to:

- Perform Exploratory Data Analysis (EDA)
- Analyze class imbalance
- Engineer suitable target classes
- Train multiple machine learning classifiers
- Compare model performance
- Identify the most important chemical properties affecting wine quality

---

## 📂 Dataset

The dataset contains physicochemical measurements of wine samples, including:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (Target)

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The project includes:

- Dataset inspection
- Statistical summary
- Missing value analysis
- Distribution plots
- Correlation heatmap
- Class distribution analysis

---

## ⚙️ Feature Engineering

The original quality scores were converted into binary classes:

| Quality Score | Class |
|--------------|-------|
| < 6 | Bad (0) |
| ≥ 6 | Good (1) |

This transformation simplifies the prediction task and reduces the impact of class imbalance.

---

## 🤖 Machine Learning Models

The following classifiers were trained and evaluated:

- 🌳 Random Forest Classifier
- 🔵 Support Vector Classifier (SVC)
- 🟠 Stochastic Gradient Descent (SGD) Classifier

---

## 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| 🌳 Random Forest | **80.35%** |
| 🔵 Support Vector Classifier | **78.60%** |
| 🟠 SGD Classifier | **62.88%** |

### Best Model

**Random Forest** achieved the highest accuracy and the most balanced performance across evaluation metrics, making it the preferred model for deployment.

---

## 🔍 Feature Importance

The Random Forest model identified the following as the most influential features:

1. Alcohol
2. Sulphates
3. Total Sulfur Dioxide
4. Volatile Acidity
5. Density

Alcohol content was found to be the strongest predictor of wine quality.

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Multi-class classification
- Handling class imbalance using SMOTE
- Model deployment using Streamlit or Flask

---

## 👨‍💻 Author

**Bhavyaa Bansal**

Data Analytics Intern

---

## ⭐ If you found this project useful, consider giving it a star!