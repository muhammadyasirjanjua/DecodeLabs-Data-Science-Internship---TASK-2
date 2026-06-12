# DecodeLabs Data Science Internship - Task 2

## Fraud Detection Pipeline Using Supervised Learning

This project was completed as part of the DecodeLabs Data Science Internship Program. The objective is to build a machine learning pipeline capable of detecting fraudulent transactions in a highly imbalanced dataset using classification algorithms and proper evaluation techniques.

## Project Overview

Fraud detection is a critical application of machine learning where identifying the minority class is more important than achieving high overall accuracy. This project focuses on handling class imbalance, training classification models, and evaluating performance using appropriate metrics.

## Objectives

- Perform data preprocessing and cleaning
- Handle class imbalance using SMOTE
- Train and compare multiple classification models
- Evaluate models using Precision, Recall, F1-Score, and ROC-AUC
- Identify the most effective model for fraud detection

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Imbalanced-Learn (SMOTE)
- Jupyter Notebook

## Machine Learning Models

The following classification algorithms were implemented and evaluated:

- Logistic Regression
- Random Forest Classifier

## Workflow

1. Load and explore the dataset
2. Perform data preprocessing
3. Analyze class distribution
4. Apply SMOTE to balance the dataset
5. Split data into training and testing sets
6. Train classification models
7. Evaluate model performance
8. Compare results and select the best-performing model

## Evaluation Metrics

Since fraud detection datasets are highly imbalanced, accuracy alone can be misleading. The models were evaluated using:

- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

## Project Structure
