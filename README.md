# Titanic - Machine Learning from Disaster 🚢
This repository contains my solution for the Kaggle Titanic competition. The goal is to use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

## 🎯 Project Goal
To build a binary classification model that predicts whether a passenger survived ($1$) or deceased ($0$) based on features like age, gender, and ticket class.

## 🛠️ Tech Stack
### Language: 
Python

### Libraries: 
pandas, numpy (Data handling), seaborn, matplotlib (Visualization), scikit-learn (Machine Learning), xgboost

### Environment: Jupyter Notebook 

## 📊 Workflow
Exploratory Data Analysis (EDA): Identifying correlations between features (e.g., "Women and children first").

Data Cleaning: Handling missing values in the Age, Cabin, and Embarked columns.

Feature Engineering: Creating new features like FamilySize or extracting Title from names.

Modeling: 1. Logistic Regression 2. Xgboost

Evaluation: Using cross-validation score
