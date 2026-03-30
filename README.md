# New_INSE-6220-2254-MM
PCA-based Network Intrusion Detection using Machine Learning


# PCA-Based Network Intrusion Detection Using Machine Learning

## Overview
This project applies Principal Component Analysis (PCA) to the NSL-KDD network intrusion dataset in order to reduce dimensionality and analyze the impact of PCA on multiple machine learning classifiers.

## Dataset
- NSL-KDD Dataset
- Source: https://www.kaggle.com/datasets/hassan06/nslkdd

## Methodology
1. Exploratory Data Analysis (EDA)
2. Data preprocessing and feature scaling
3. Principal Component Analysis (PCA)
4. Classification using:
   - K-Nearest Neighbors
   - Linear SVM
   - RBF SVM
   - Random Forest
   - AdaBoost
   - Naive Bayes
5. Evaluation using Accuracy, Precision, Recall, F1-score
6. Cross-validation analysis

## Notebooks
- `01_EDA_NSLKDD.ipynb`

## Results
Random Forest achieved the best overall performance with high F1-score and low variance across folds.

## Tools
- Python
- Scikit-learn
- Pandas
- Seaborn
- Google Colab

## Author
Zar Chi Phyo

