# Credit Card Fraud Detection using Machine Learning

A comprehensive Machine Learning project for detecting fraudulent credit card transactions using data preprocessing, feature engineering, handling class imbalance, model evaluation, and performance comparison.

---

##  Project Overview

Credit card fraud is one of the most challenging problems in financial technology due to the highly imbalanced nature of transaction data. This project focuses on building robust fraud detection models by applying data preprocessing, exploratory data analysis (EDA), outlier detection, feature selection, imbalance handling, and multiple machine learning algorithms.

The project compares different classification models to identify the most effective approach for fraud detection while minimizing false negatives and false positives.

---

## Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Missing Value Detection
- Outlier Detection & Removal
- Feature Engineering
- Information Value (IV) Analysis
- Weight of Evidence (WoE)
- Feature Scaling
- Class Imbalance Handling
- Random Oversampling
- Random Undersampling
- SMOTE
- Model Training & Hyperparameter Tuning
- Model Evaluation using Multiple Metrics
- Confusion Matrix Visualization
- ROC-AUC Analysis
- Precision-Recall Analysis

---

## Datasets

This project uses two publicly available Kaggle datasets.

### Dataset 1: Credit Card Fraud Detection Dataset (2023)

**Kaggle Link**

https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023

**Description**

- Large-scale synthetic credit card transaction dataset
- Contains anonymized features
- Binary classification (Fraud / Non-Fraud)
- Suitable for large-scale fraud detection experiments

---

### Dataset 2: Credit Card Fraud Dataset

**Kaggle Link**

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

**Description**

- Realistic fraud transaction dataset
- Highly imbalanced
- Binary classification problem
- Used to evaluate model robustness on skewed distributions

---

## Exploratory Data Analysis

The project includes:

- Class Distribution
- Feature Distribution
- Correlation Heatmap
- Histograms
- Boxplots
- Violin Plots
- KDE Plots
- Outlier Analysis

---

## Data Preprocessing

- Removing Duplicate Records
- Missing Value Handling
- Feature Scaling
- Z-Score Based Outlier Detection
- IQR Outlier Detection
- Data Normalization
- Feature Selection

---

##  Feature Engineering

- Information Value (IV)
- Weight of Evidence (WoE)
- Correlation Analysis
- Feature Importance
- Statistical Analysis

---

##  Handling Class Imbalance

Different balancing techniques were evaluated:

- Random Undersampling

## Machine Learning Models

The following algorithms were implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Extra Trees Classifier
- XGBoost Classifier

Hyperparameter tuning was performed using:

- GridSearchCV
- Cross Validation (CV = 5)
- KFOLD Technique

---

##  Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Imbalanced-Learn
- SciPy
- Jupyter Notebook

---

## Project Structure

```
Credit-Card-Fraud-Detection/
│
├── data/
│   ├── creditcard_2023.csv
│   ├── credit_card.csv
│
├── notebooks/
│   ├── credit_card_fraud.ipynb
│   ├── Fraud_detection_imbalance_dataset.ipynb
│
├── README.md

```

---



