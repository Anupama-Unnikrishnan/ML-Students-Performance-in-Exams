# Student Performance Prediction using Machine Learning

## Overview
This project predicts whether a student will Pass or Fail based on demographic and academic factors using Machine Learning classification models.

The goal is to demonstrate the complete ML workflow:
data preprocessing, feature engineering, model training, evaluation, and prediction.


## Dataset
- Source: Kaggle – Students Performance in Exams
- Size: 1000 records
- Features: Gender, parental education, lunch type, test preparation, scores


## Problem Statement
To predict a student's academic outcome (Pass / Fail) using non-score attributes and engineered features.


## Approach
1. Data loading and cleaning  
2. Feature engineering (average score calculation)  
3. Target creation (Pass / Fail classification)  
4. Categorical encoding  
5. Train–test split  
6. Model training using Random Forest  
7. Model evaluation  
8. New student prediction  


## Model Used
- Random Forest Classifier

Chosen for:
- Handling non-linear relationships
- Robust performance on tabular data
- Reduced overfitting


## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn


##  How to Run
```bash
pip install -r requirements.txt

