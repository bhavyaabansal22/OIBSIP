# Customer Segmentation Analysis using RFM & K-Means Clustering

## 📌 Project Overview

This project was completed as **Task 2** during my **Data Analytics Internship at Oasis Infobyte**.

The objective of this project is to perform **customer segmentation** on an e-commerce dataset using **RFM (Recency, Frequency, Monetary) Analysis** and **K-Means Clustering**. The identified customer segments help businesses understand purchasing behavior and develop targeted marketing strategies to improve customer retention and revenue.

---

## 🎯 Objectives

- Analyze customer purchasing behaviour
- Perform RFM (Recency, Frequency, Monetary) Analysis
- Standardize customer features
- Determine the optimal number of clusters using the Elbow Method
- Segment customers using K-Means Clustering
- Visualize customer clusters
- Profile each customer segment
- Recommend marketing strategies for each cluster

---

## 📂 Dataset

**Dataset:** E-commerce Customer Behaviour Analysis

The dataset contains customer transaction records, including:

- Customer ID
- Purchase Date
- Product Category
- Product Price
- Quantity
- Total Purchase Amount
- Payment Method
- Customer Age
- Returns
- Customer Name
- Gender
- Churn

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

### 1. Data Loading & Inspection

- Loaded the dataset
- Explored data structure
- Checked data types
- Identified missing values
- Removed duplicate columns

---

### 2. Data Preprocessing

- Converted Purchase Date to datetime format
- Handled duplicate information
- Prepared transaction data for analysis

---

### 3. Exploratory Data Analysis

Performed descriptive statistics including:

- Average Purchase Value
- Purchase Frequency
- Customer Lifetime Value (CLV)

Visualizations include:

- Purchase Frequency Distribution
- Customer Lifetime Value Distribution
- RFM Feature Distributions
- Correlation Heatmap

---

### 4. RFM Analysis

The following customer behaviour metrics were calculated:

### Recency (R)

Number of days since the customer's most recent purchase.

### Frequency (F)

Total number of purchases made by each customer.

### Monetary (M)

Total purchase amount spent by each customer.

---

### 5. Feature Scaling

Standardized the RFM features using **StandardScaler** before clustering to ensure equal contribution of each feature.

---

### 6. K-Means Clustering

- Applied the Elbow Method
- Determined the optimal number of clusters
- Segmented customers using K-Means

---

### 7. Cluster Visualization

Generated multiple visualizations including:

- Frequency vs Monetary
- Recency vs Monetary
- Customers per Cluster
- Cluster Profile Analysis

---

## 📈 Key Insights

- Customer purchase behaviour varies significantly across different segments.
- A small group of customers contributes a large portion of the total revenue.
- Most customers have relatively low purchase frequency, while only a few customers make repeated purchases.
- Customer segmentation enables businesses to identify high-value and low-engagement customers more effectively.

---

## 💡 Marketing Recommendations

### 🏆 Loyal / High-Value Customers

- Loyalty reward programs
- Exclusive offers
- Early access to new products

### 🌱 Potential Loyal Customers

- Personalized product recommendations
- Cross-selling
- Reward points

### 🛍️ Occasional Customers

- Seasonal promotions
- Email campaigns
- Limited-time discounts

### ⚠️ At-Risk Customers

- Win-back campaigns
- Personalized discount coupons
- Reminder emails
- Retention offers

---


## 🚀 Learning Outcomes

Through this project, I gained hands-on experience in:

- Customer Segmentation
- RFM Analysis
- Feature Engineering
- Data Standardization
- K-Means Clustering
- Elbow Method
- Customer Profiling
- Business Insight Generation
- Data Visualization

---

## 📌 Internship Information

**Track:** Data Analytics Internship

**Task:** Customer Segmentation Analysis

**Organization:** Oasis Infobyte
---

## ⭐ If you found this project helpful, feel free to star this repository!