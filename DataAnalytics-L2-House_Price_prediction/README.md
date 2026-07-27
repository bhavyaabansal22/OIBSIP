# 🏡 House Price Prediction using Linear Regression

## 📌 Overview

This project develops and evaluates a **Linear Regression** model to predict house prices based on various property features such as area, number of bedrooms, bathrooms, parking availability, furnishing status, and other amenities.

The project follows a complete machine learning workflow, including data exploration, preprocessing, feature engineering, model training, evaluation, interpretation, and comparison with regularized regression models (Ridge and Lasso).

---

## 🎯 Objective

The primary objective of this project is to:

- Predict house prices using Linear Regression.
- Perform Exploratory Data Analysis (EDA).
- Handle categorical variables using One-Hot Encoding.
- Evaluate the model using regression metrics.
- Interpret feature importance through coefficient analysis.
- Compare Linear Regression with Ridge and Lasso Regression.

---

## 📂 Dataset

The dataset contains residential housing information with the following features:

| Feature | Description |
|----------|-------------|
| Price | Target variable (House Price) |
| Area | Area of the house |
| Bedrooms | Number of bedrooms |
| Bathrooms | Number of bathrooms |
| Stories | Number of floors |
| Mainroad | Connected to main road |
| Guestroom | Availability of guest room |
| Basement | Availability of basement |
| Hot Water Heating | Hot water heating facility |
| Air Conditioning | Air conditioning availability |
| Parking | Number of parking spaces |
| Preferred Area | Located in preferred area |
| Furnishing Status | Furnished / Semi-Furnished / Unfurnished |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

- Load Dataset
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Selection
- One-Hot Encoding
- Correlation Analysis
- Train-Test Split (80:20)
- Linear Regression Model
- Model Evaluation
- Actual vs Predicted Analysis
- Residual Analysis
- Coefficient Interpretation
- Ridge & Lasso Regression Comparison

---

## 📈 Model Evaluation

### Linear Regression

- Mean Squared Error (MSE): **1,754,318,687,330.71**
- Root Mean Squared Error (RMSE): **1,324,506.96**
- R² Score: **0.6529**

### Ridge Regression

- R² Score: **0.6525**

### Lasso Regression

- R² Score: **0.6529**

---

## 📷 Visualizations Included

- House Price Distribution
- Numerical Feature Distributions
- Correlation Heatmap
- Actual vs Predicted Prices
- Residual Plot
- Coefficient Importance
- Regression Model Comparison

---

## 📌 Key Insights

- House prices exhibit a right-skewed distribution.
- Area and bathrooms are among the strongest positive predictors.
- Air conditioning, preferred area, and parking positively influence house prices.
- Unfurnished houses generally have a negative impact on price.
- Linear Regression, Ridge, and Lasso achieved similar predictive performance.

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Feature engineering
- Polynomial Regression
- Random Forest Regression
- XGBoost Regressor
- Cross-validation

---

## 👩‍💻 Author

**Bhavyaa Bansal**

Data Analytics Intern

Oasis Infobyte