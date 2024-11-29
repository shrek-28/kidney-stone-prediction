# Binary Classification with a Tabular Kidney Stone Prediction Dataset 

## Flow of the Project 
![[images/Screenshot 2024-11-29 205811.png](https://github.com/shrek-28/kidney-stone-prediction/images/target_var_count.png)] 

This image describes the general flow, of the project and design of the project, where the [dataset](https://www.kaggle.com/competitions/playground-series-s3e12/data) was obtained from Kaggle. Extensive exploratory data analysis (EDA) was conducted with the data, followed by preprocessing. Three machine learning classification models were used, Logistic Regression, K-Nearest Neighbours and Support Vector Machines. The SVM model yielded the highest AUC score of 0.84. 

## Step 1: Exploratory Data Analysis and its Results 

### Univariate Analysis
In the univariate analysis of the variables, the following facts were obtained: 
- Gravity distribution was multimodal, indicating that the data can be split into two or more groups.
- The distributions of pH and calc were highly skewed towards the left, indicating that fixed or near-fixed upper boundaries are in play.
- Distributions of osmo and urea were a multimodal but nearly normal distribution.
- The distribution of cond was skewed to the right and was a multimodal distribution, indicating a fixed lower boundary

Visualizations of Graphs:
![images/calc_dist.png]
![images/cond_dist.png]
![images/gravity_dist.png]
![images/osmo_dist.png]
![images/ph_dist.png]
![images/urea_dist.png]

### Target Variable Analysis 
The occurrence of target variable 1 is higher than target variable 0. This indicates that the models can be biased towards the majority class, and can lead to poor generalizations for the target variable 0 predictions 

![images/target_var_count.png]

### Outlier Analysis 
- No outliers were observed in the variable analysis of urea, cond, calc and osmo, with dispersions being fairly equal for all 4 variables.
- pH and gravity have minor amount of outliers.

