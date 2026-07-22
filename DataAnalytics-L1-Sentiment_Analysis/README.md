# Task 4 - Sentiment Analysis using Machine Learning

## Oasis Infobyte Data Analytics Internship

### Objective

The objective of this project is to build a Machine Learning model capable of automatically classifying Amazon customer reviews into **Positive**, **Negative**, and **Neutral** sentiments. The project demonstrates an end-to-end Natural Language Processing (NLP) pipeline including text preprocessing, feature engineering, model training, evaluation, visualization, and performance comparison.

---

## Dataset

The dataset used in this project is **not included** in this repository due to its large file size.

**Dataset:** Amazon Product Reviews

**Source:** Kaggle  
https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews

### Project Setup

1. Download the dataset from the Kaggle link above.
2. Create a folder named `data` inside the project directory.
3. Place the downloaded file in the `data` folder as shown below:

```
DataAnalytics-L1-Sentiment_Analysis/
│
├── data/
│   └── Reviews.csv
│
├── notebook.ipynb
├── README.md
├── requirements.txt
└── images/
```

The notebook expects the dataset at the following path:

```python
data/Reviews.csv
```

> **Note:** The dataset has been excluded from this repository because it exceeds GitHub's recommended file size limits. Please download it from the Kaggle source before running the notebook.

### Features

- Id
- ProductId
- UserId
- ProfileName
- HelpfulnessNumerator
- HelpfulnessDenominator
- Score
- Time
- Summary
- Text

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

- Imported dataset
- Checked dataset information
- Identified missing values

### 2. Data Preprocessing

- Created sentiment labels from review scores
- Converted text to lowercase
- Removed punctuation
- Tokenized text
- Removed stopwords
- Applied lemmatization

### 3. Feature Extraction

- Converted cleaned text into numerical vectors using **TF-IDF Vectorizer**

### 4. Machine Learning Models

- Multinomial Naive Bayes
- Logistic Regression

### 5. Model Evaluation

The following metrics were used:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### 6. Visualizations

- Sentiment Distribution
- WordClouds for each sentiment
- Accuracy Comparison
- Precision / Recall / F1 Comparison
- Confusion Matrix
- Class-wise Performance Comparison

### 7. Error Analysis

Misclassified reviews were analyzed to understand model limitations.

---

## Results

| Model | Accuracy |
|---------|----------|
| Naive Bayes | **79.20%** |
| Logistic Regression | **87.69%** |

Logistic Regression outperformed Naive Bayes across nearly all evaluation metrics and was selected as the final model.

---

## Conclusion

This project successfully demonstrates an end-to-end sentiment analysis workflow using Natural Language Processing and Machine Learning techniques. Logistic Regression produced the best performance and can be effectively applied for customer feedback analysis, product review classification, and brand sentiment monitoring.

---

## Author

**Bhavyaa Bansal**

Data Analytics Intern

Oasis Infobyte