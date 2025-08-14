## AI-ML-Task-7

## Support Vector Machines (SVM) 

## Overview

This project involves building and evaluating Support Vector Machine (SVM) models to classify tumors as malignant or benign using the Breast Cancer dataset. The workflow covers data preprocessing, training SVMs with different kernels, dimensionality reduction for visualization, hyperparameter tuning using GridSearchCV, and performance evaluation through cross-validation.

## Dataset

The dataset used in this project is the Breast Cancer Wisconsin dataset, containing 569 entries with 30 numerical features describing cell nucleus characteristics and one target variable indicating tumor type.

## Tools and Libraries

Python

Pandas

NumPy

Matplotlib

Scikit-learn

## Steps


1. Import and Explore Dataset

Loaded the dataset using Pandas and checked data types, shape and missing values.

Dropped the ID column as it’s not useful for classification.

Encoded the target variable (diagnosis) into numerical form.

2. Split Data

Split into training and testing sets (70% train, 30% test).

3. Train SVM Models

Trained an SVM with a linear kernel.

Trained an SVM with an RBF kernel.

4. Visualize Decision Boundaries

Reduced features to 2D using PCA for visualization.

Plotted the decision boundary for the linear kernel model.

5. Hyperparameter Tuning

Created a Pipeline with StandardScaler and SVC.

Tuned C and gamma parameters using GridSearchCV with 5-fold cross-validation.


6. Cross-Validation Evaluation

Evaluated the best model using cross-validation:


## Output

High accuracy in cross-validation confirms strong model performance.

PCA visualization shows clear separation between malignant and benign cases.
