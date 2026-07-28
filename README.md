# 🧬 Genetic Disorder Data Analysis & Machine Learning Model Comparison

A supervised machine learning project that explores a pediatric genetic disorder dataset and compares three classification models to predict patient survival outcomes (**Alive** vs **Dead**).

---

## 📌 Project Objective

The aim of this project was to clean and analyse a real-world genetic disorder dataset, develop predictive classification models, and compare their performance to identify the most suitable model for predicting high-risk patients requiring urgent clinical attention.

---

## 📊 Dataset

The dataset contains demographic, clinical, laboratory, hereditary and genetic information for pediatric patients diagnosed with genetic disorders.

**Target Variable**

- **Status** (Alive / Dead)

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔬 Project Workflow

This project covered the complete machine learning pipeline:

- Data importing and inspection
- Data cleaning and preprocessing
- Feature selection
- Exploratory Data Analysis (EDA)
- Categorical variable encoding
- Train-test split
- Model training
- Model comparison and evaluation

---

## 📈 Exploratory Data Analysis

The analysis explored:

- Distribution of patient demographics
- Genetic inheritance patterns
- Relationships between clinical variables
- Disorder frequencies and subclasses
- Correlation between predictor variables

### Key Findings
- Mitochondrial genetic disorders were the most prevalent disorder category.
- Leigh Syndrome was the most common disorder subclass.
---

## 🤖 Models Evaluated

- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

Models were compared using standard classification metrics including Accuracy, Sensitivity (Recall), Specificity and Precision.

---

## 🏆 Model Comparison

The Decision Tree model demonstrated the highest sensitivity (**39%**) for identifying deceased patients, making it the most clinically useful among the three models for this objective.

However, overall model performance remained modest (**51% accuracy**), indicating that the dataset presents a challenging classification problem and would benefit from additional feature engineering, improved data quality, and more robust validation techniques.

---

## 💻 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Selection
- Data Preprocessing
- Classification Modelling
- Model Evaluation
- Healthcare Data Analytics
- Python for Machine Learning
