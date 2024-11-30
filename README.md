# Binary Classification with a Tabular Kidney Stone Prediction Dataset 

## Project Overview 
This project aims to predict the likelihood of kidney stone formation using a binary classification approach on a tabular dataset. The dataset was sourced from [Kaggle's Playground Series](https://www.kaggle.com/competitions/playground-series-s3e12/data)

The pipeline involves Exploratory Data Analysis (EDA), Data Preprocessing, and the implementation of three machine learning models:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machines (SVM)
Among these, the SVM model achieved the highest performance with an AUC score of 0.84.

## Flow of the Project 
![image](https://github.com/shrek-28/kidney-stone-prediction/blob/main/images/Screenshot%202024-11-29%20205811.png)

The project is divided into three main stages:
1. Exploratory Data Analysis (EDA):
- Comprehensive analysis to understand feature distributions, correlations, and target variable characteristics.
- Identified insights that informed the preprocessing steps and modeling decisions.
  
📄 [View Notebook](https://github.com/shrek-28/kidney-stone-prediction/blob/main/Exploratory%20Data%20Analysis.ipynb)

2. Data Preprocessing:
- Addressed missing values, outliers, and feature transformations.
- Engineered features for better predictive power.
- Scaled data for algorithms sensitive to feature magnitudes.
  
📄 [View Notebook](https://github.com/shrek-28/kidney-stone-prediction/blob/main/Data%20Preprocessing.ipynb)

3. Machine Learning Models 
- Implemented three machine learning models.
- Hyperparameter tuning using GridSearchCV for optimal performance.
- Compared models based on metrics like AUC, precision, and recall.
  
📄 [View Notebook](https://github.com/shrek-28/kidney-stone-prediction/blob/main/Machine%20Learning%20Models.ipynb)

