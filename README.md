# 🧬 Genetic Disorder Data Analysis & Machine Learning Model Comparison

A supervised machine learning project that analyzes a pediatric genetic disorder dataset to predict patient survival status (**Alive** vs **Dead**) and compares the performance of three classification models.

---

## 📌 Project Overview

This project applies data preprocessing, exploratory data analysis (EDA), and supervised machine learning techniques to identify patterns associated with patient outcomes. Multiple classification models were developed and evaluated to compare their predictive performance on a real-world healthcare dataset.

---

## 🎯 Project Objective

- Clean and preprocess a genetic disorder dataset.
- Explore clinical, genetic, and demographic patterns through EDA.
- Build and compare multiple machine learning classification models.
- Evaluate model performance for predicting patient survival status.

---

## 📊 Dataset

The dataset consists of pediatric patient records containing:

- Demographic information
- Family and genetic history
- Laboratory findings
- Clinical symptoms
- Genetic disorder classifications

**Target Variable:** `Status (Alive / Dead)`

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Project Workflow

- Data Import & Inspection
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Selection & Encoding
- Train-Test Split
- Model Training
- Model Evaluation & Comparison

---

## 📈 Exploratory Data Analysis

EDA was performed using univariate, bivariate, and multivariate techniques to understand patient demographics, inheritance patterns, laboratory findings, and disorder distributions.

### Key Findings
- Mitochondrial genetic disorders were the most prevalent disorder category.
- Leigh Syndrome was the most common disorder subclass.
- Mitochondrial disorders accounted for the highest proportion of both surviving and deceased patients.

---

## 🤖 Models Evaluated

- Support Vector Classifier (SVC)
- Decision Tree
- Random Forest

Models were evaluated using **Accuracy**, **Sensitivity (Recall)**, and **Specificity**.

### Model Performance

| Model | Accuracy | Sensitivity | Specificity |
|--------|---------:|------------:|------------:|
| Support Vector Classifier | 61% | 0% | 100% |
| Decision Tree | 51% | 39% | 58% |
| Random Forest | 57% | 24% | 78% |

Overall, the models demonstrated modest predictive performance, reflecting the complexity of the clinical classification task. The comparison highlights the trade-offs between sensitivity and specificity across different machine learning algorithms when applied to healthcare data.

---

## 🚀 Project Impact
The analysis provides insights into genetic disorder patterns while illustrating the application of predictive analytics to support clinical risk stratification and evidence-based healthcare decision-making.





