# 🧹 Task 3: Cleaning Data

## 📌 Internship Details

- **Internship:** Oasis Infobyte
- **Track:** Data Analytics
- **Task:** Cleaning Data
- **Intern:** Bhavyaa Bansal

---

## 📖 Project Overview

Data quality is a critical prerequisite for reliable data analysis and machine learning. In this project, a deliberately messy Google Play Store dataset was cleaned and transformed into an analysis-ready dataset by identifying and resolving common data quality issues.

The project demonstrates professional data cleaning techniques including handling missing values, removing duplicate records, correcting data types, standardizing inconsistent formats, detecting outliers, and documenting every cleaning decision.

---

## 🎯 Objective

To systematically clean a raw dataset by:

- Performing a comprehensive data quality assessment
- Handling missing values using appropriate imputation techniques
- Removing duplicate records
- Standardizing inconsistent data formats
- Detecting and evaluating outliers using the IQR method
- Correcting incorrect data types
- Comparing dataset quality before and after cleaning
- Exporting the cleaned dataset for further analysis

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

**Dataset:** Google Play Store Apps Dataset

Dataset contains information about Android applications including:

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Current Version
- Android Version

---

## 🔍 Data Cleaning Process

### 1. Data Quality Assessment

- Dataset dimensions
- Missing value analysis
- Duplicate detection
- Data type inspection
- Statistical summary
- Identification of value anomalies

---

### 2. Missing Value Handling

Different strategies were applied based on the nature of each column:

| Column | Strategy |
|---------|----------|
| Rating | Median Imputation |
| Type | Mode Imputation |
| Content Rating | Mode Imputation |
| Android Version | Mode Imputation |
| Current Version | Filled with "Unknown" |

---

### 3. Duplicate Removal

- Identified duplicate records
- Removed duplicate rows
- Verified duplicate count after cleaning

---

### 4. Data Standardization

Performed standardization on:

- Install counts
- Price values
- Application size
- Date formatting
- Text formatting

---

### 5. Data Type Correction

Converted columns into appropriate data types including:

- Integer
- Float
- Datetime

---

### 6. Outlier Detection

Applied the **Interquartile Range (IQR)** method to identify outliers in:

- Rating
- Reviews
- Size
- Installs
- Price

Outliers were retained when they represented genuine observations rather than data entry errors.

---

### 7. Final Dataset

Generated a cleaned and analysis-ready dataset and exported it as:

```
google_playstore_cleaned.csv
```

---

## 📈 Key Outcomes

- Missing values handled appropriately
- Duplicate records removed
- Invalid records eliminated
- Consistent formatting across columns
- Correct data types assigned
- Outliers evaluated and documented
- Clean dataset exported successfully

---

## 👩‍💻 Author

**Bhavyaa Bansal**

Data Analytics Intern

Oasis Infobyte