# MSc Big Data Analytics - Data Mining Project

This repository contains the solutions for the Data Mining course (CMM704) as part of the MSc Big Data Analytics program. The project focuses on data preprocessing, feature transformation, dimensionality reduction, and classification techniques using Logistic Regression and Support Vector Machines (SVM) on a banking dataset.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Dimensionality Reduction](#dimensionality-reduction)
- [Classification Models](#classification-models)
- [Results and Analysis](#results-and-analysis)
- [Conclusion](#conclusion)
- [Author](#author)

## Project Overview

This project applies various data mining techniques to preprocess, analyze, and model a banking dataset. The primary objectives include:
1. Handling missing values and outliers.
2. Transforming and scaling features.
3. Reducing dimensionality using Singular Value Decomposition (SVD).
4. Applying Logistic Regression and Support Vector Machine (SVM) classifiers.

## Data Preprocessing

- **Handling Missing Values**: Dropped or imputed columns with missing values based on their impact on the model.
- **Outlier Detection**: Identified outliers using boxplots and handled them appropriately to avoid skewing results.

## Feature Engineering

- **Feature Transformation**: Applied transformations such as logarithmic and exponential adjustments to normalize skewed distributions.
- **Feature Coding**: Used label encoding for categorical variables, preserving the feature space without expansion.
- **Scaling**: Scaled features to improve model performance and reduce bias.

## Dimensionality Reduction

- **SVD**: Performed Singular Value Decomposition to identify the most significant features for reducing computational load.

## Classification Models

- **Logistic Regression**: Implemented as a baseline classification model.
- **Support Vector Machine**: Applied SVM and compared its performance with Logistic Regression.

## Results and Analysis

- **Confusion Matrix**: Evaluated model predictions with confusion matrices for both Logistic Regression and SVM.
- **ROC Curve**: Used ROC curves to assess the diagnostic capability of each model.
- **Performance Metrics**: Compared models using accuracy, recall, and F1-score, with SVM outperforming Logistic Regression on this dataset.

## Conclusion

The project concludes that the Support Vector Machine performs better than Logistic Regression for this banking dataset, achieving higher accuracy and recall. The findings underscore the suitability of SVM for classification tasks involving this type of data.

## Author

- **Don Manula Ransika Udugahapattuwa**
  - IIT Student ID: 20200361
  - RGU Student ID: 2016629

---

**Note**: Please refer to the detailed documentation and results within the report for in-depth insights into each step of the project.
