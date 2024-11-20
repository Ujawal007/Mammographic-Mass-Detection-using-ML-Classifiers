# Mammographic Mass Detection using ML Classifiers

## Overview
This project focuses on detecting mammographic masses using machine learning classifiers. It applies data preprocessing, oversampling using SMOTE, and randomization techniques to enhance the robustness of the models. Datasets such as `BCR_dataset` and `balanced_dataset` are used for training and evaluation.

---

## Files in the Repository

1. **Notebook**:
   - `BreastCancer_detection_using_SMOTE.ipynb`: Contains all the data preprocessing, randomization, SMOTE application, model training, and evaluation.

2. **Datasets**:
   - `BCR_dataset`: The original breast cancer dataset used for analysis.
   - `balanced_dataset`: The dataset created after applying SMOTE to balance the classes.

3. **README.md**: Documentation of the project (this file).

---

## Features of the Project

- **Data Preprocessing**:
  - Handling missing data and feature engineering.
  - Normalizing features for optimal machine learning performance.

- **Randomization**:
  - Applied randomization techniques during data preprocessing to reduce bias and ensure diverse train-test splits.

- **SMOTE Application**:
  - Synthetic Minority Oversampling Technique (SMOTE) is applied to address the imbalance in the dataset.

- **Model Training**:
  - Implementing machine learning classifiers such as Logistic Regression, Random Forest, and Support Vector Machines (SVM).

- **Model Evaluation**:
  - Accuracy, precision, recall, F1 score, and ROC-AUC are used as evaluation metrics.

---

## Prerequisites

Ensure the following Python libraries are installed:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `imbalanced-learn`
- `jupyter`

Install the dependencies using:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn
