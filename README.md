# Employee Salary Prediction

This project is built to classify whether a person's salary is greater than or less than $50K based on demographic and work-related features. It uses the Adult Income Dataset and applies Logistic Regression for classification.

## Overview

- **Model Used:** Logistic Regression  
- **Dataset:** UCI Adult Income Dataset (`adult.csv`)  
- **Language:** Python  
- **Platform:** Google Colab  
- **Accuracy:** ~80%  
- **Evaluation Metric:** Confusion Matrix

## Objective

Predict whether an individual earns more than $50K a year using various attributes such as:

- Age
- Education
- Occupation
- Marital Status
- Hours per week
- Native country, etc.

## Features Implemented

- Data Cleaning and Preprocessing  
- Handling Missing Values  
- Label Encoding for Categorical Variables  
- Feature Scaling using StandardScaler  
- Logistic Regression Model Training  
- Model Evaluation using Accuracy Score and Confusion Matrix  
- Visualization of Results

## Steps Followed

1. **Importing Required Libraries**  
2. **Reading the Dataset**  
3. **Data Preprocessing**
   - Handling missing values (`?`)
   - Encoding categorical columns
   - Feature scaling
4. **Splitting the Dataset**
   - Train-Test split (80-20)
5. **Model Building**
   - Logistic Regression using `sklearn`
6. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Visualization using seaborn

## Dataset Source

The dataset is publicly available on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult).

## What I Learned

- Real-world dataset preprocessing techniques  
- How to handle categorical and missing data  
- Implementation of logistic regression in a practical project  
- Evaluation techniques for classification problems

## Future Improvements

- Try other classification models (Random Forest, XGBoost, etc.)  
- Apply Grid Search for hyperparameter tuning  
- Add performance metrics like precision, recall, F1-score  
- Build a simple web UI for input & prediction
