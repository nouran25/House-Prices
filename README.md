# House Prices: Advanced Regression Techniques
Kaggle House Prices Solution
# Description:

This repository contains a solution for the House Prices - Advanced Regression Techniques competition on Kaggle. The goal of this competition is to use machine learning to create a model that predicts the sales price for each house.

# Dataset
The dataset is provided by Kaggle and includes different kinds of information about the houses such as their overall condition, year built, lot area, neighborhood, and the sale price.
# Libraries
The following libraries are used in the project:

pandas
numpy
seaborn
matplotlib
xgboost
sklearn
catboost
# Key Features:

Data Exploration and Preprocessing: Initial analysis of the dataset to understand the data structure and identify any missing or outlier values.
Feature Engineering: Creation of new features that could potentially improve the model's performance.
Model Training and Evaluation: Utilization of CatBoost and XGBoost models for training and evaluation. The models were trained using K-Fold cross-validation to ensure robust performance.
Hyperparameter Tuning: Experimentation with different hyperparameters to optimize the models' performance.
Model Combination: Combining predictions from both models using a weighted average to generate the final house price predictions.
# Technologies Used:

Python: The primary programming language used for data manipulation, analysis, and model training.
Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
CatBoost and XGBoost: For model training and prediction.
Scikit-learn: For cross-validation and other utility functions.
# Result:

The model achieves a mean RMSE score of 0.12913 with a standard deviation of the RMSE scores across the KFold cross-validation.
