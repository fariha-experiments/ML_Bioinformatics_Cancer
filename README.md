Breast Cancer Molecular Subtype Classification
Overview

Breast cancer is not a single disease. Different molecular subtypes respond differently to treatment, making accurate classification an important step in precision medicine.

This project explores how machine learning can classify breast cancer molecular subtypes using gene expression data from the GSE45827 dataset. The project was completed as part of the IISc Pravega Bioinformatics for Cancer Research Workshop and served as my first hands-on experience applying machine learning to real biomedical data.

Objective

Build an end-to-end machine learning pipeline that predicts breast cancer molecular subtypes from gene expression profiles while gaining practical experience with biomedical data preprocessing, dimensionality reduction, model training, and evaluation.

Dataset

Source: GSE45827 Gene Expression Dataset

The dataset contains gene expression profiles labelled into four molecular breast cancer subtypes:

Luminal A
Luminal B
HER2-enriched
Triple Negative
Workflow
1. Data Preprocessing
Loaded and explored the gene expression dataset
Encoded categorical labels
Standardized numerical features
2. Dimensionality Reduction

Applied Principal Component Analysis (PCA) to reduce the high-dimensional gene expression data while preserving important variance.

3. Model Development

Implemented and compared multiple classification algorithms:

Random Forest
Logistic Regression
Support Vector Machine (SVM)
4. Model Evaluation

Evaluated model performance using:

Accuracy
Confusion Matrix
Classification Report
Tech Stack
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Key Learnings

This project introduced me to several core machine learning concepts:

Working with high-dimensional biomedical datasets
Feature scaling and preprocessing
Dimensionality reduction using PCA
Comparing multiple classification models
Evaluating classification performance
Translating biological datasets into machine learning workflows
Future Improvements
Hyperparameter tuning
Cross-validation
Feature selection
Explainability using SHAP
Larger biomedical datasets
Deep learning comparison
