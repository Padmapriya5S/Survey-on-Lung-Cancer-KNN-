**Project Overview**

This project focuses on predicting lung cancer occurrence using a K-Nearest Neighbors (KNN) classifier trained on patient survey data.
The dataset is retrieved from Snowflake, processed using Python, and evaluated using Stratified Cross-Validation to ensure robust performance on imbalanced medical data.
KNN is a distance-based algorithm, making proper preprocessing and evaluation critical for reliable predictions.

**Objective**

Predict lung cancer risk using survey-based health features
Handle class imbalance effectively
Build a leakage-free ML pipeline
Evaluate performance using F1-score

**Tech Stack Used**

Database: Snowflake
Programming Language: Python
Libraries:
pandas
snowflake-connector-python
scikit-learn
imbalanced-learn
matplotlib


**Why KNN Worked Well**

Clear separation between classes after preprocessing
SMOTE balanced minority class representation
Feature scaling improved distance-based learning
Stratified Cross-Validation ensured unbiased evaluation
