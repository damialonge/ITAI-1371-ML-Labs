# Midterm Assignment – Titanic Survival Prediction

## Overview
This end-to-end machine learning project used the famous Titanic dataset to predict whether a passenger survived the shipwreck based on features like age, gender, ticket class, and more.

## Problem Statement
Given passenger data from the Titanic disaster, build a machine learning model that accurately predicts survival outcomes. This is a **binary classification** problem (survived = 1, did not survive = 0).

## Dataset
- **Source:** Titanic dataset (via Google Colab / Kaggle)
- **Features used:** Pclass, Sex, Age, SibSp, Parch, Fare, Embarked
- **Target variable:** Survived (0 or 1)

## My Approach

### 1. Exploratory Data Analysis (EDA)
- Examined dataset shape, data types, and missing values
- Visualized survival rates by gender, class, and age
- Identified correlations between features and the target variable

### 2. Data Preprocessing & Feature Engineering
- Imputed missing `Age` values using median imputation
- Dropped the `Cabin` column due to high missing rate
- Encoded categorical variables (`Sex`, `Embarked`) using label encoding
- Dropped non-informative columns (`Name`, `Ticket`, `PassengerId`)

### 3. Model Building
- Used **Random Forest Classifier** from scikit-learn
- Split data into 80% training / 20% testing using `train_test_split`
- Trained the model on the training set

### 4. Evaluation
- Evaluated using **accuracy**, **precision**, **recall**, and **F1-score**
- Generated a **classification report** and **confusion matrix**
- Analyzed **feature importances** to understand what drove predictions

## Results
The Random Forest model achieved strong performance on the test set. Key findings:
- **Sex** and **Pclass** were the most important predictors of survival
- Female passengers and first-class passengers had significantly higher survival rates
- The model successfully captured the "women and children first" pattern in the data

## What I Learned
This project gave me hands-on experience with the complete ML workflow — from raw data to a working model. I learned how to debug preprocessing issues, interpret model metrics beyond just accuracy, and draw meaningful conclusions from feature importances.

## Tools Used
- Python
- Google Colab
- pandas, numpy, matplotlib, seaborn, scikit-learn

---
*ITAI 1371 – Midterm Project | Oludamilola Alonge*
