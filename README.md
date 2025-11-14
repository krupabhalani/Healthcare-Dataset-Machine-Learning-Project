# Healthcare-Dataset-Machine-Learning-Project

A complete end-to-end ML workflow for predicting Test Results

Project Overview:

This project focuses on building and evaluating multiple machine learning models to predict Healthcare Test Results. The goal was to practice real-world ML workflows — including data cleaning, preprocessing, model building, evaluation, and prediction. The work was performed on a structured healthcare dataset, demonstrating both regression and classification techniques for learning purposes.

Workflow Summary:

1. Data Loading & Exploration, Loaded and examined the dataset structure, Identified missing values, Performed exploratory data analysis (EDA)
2. Data Cleaning & Preprocessing, Removed irrelevant columns, One-hot encoded categorical variables, Scaled features using MinMaxScaler, Encoded the target column (Test Results) using LabelEncoder, Split data into training and testing sets

Machine Learning Models & Performance:

Regression Models
1. Multiple Linear Regression: Achieved an R² Score of -0.00065 and an MSE of 0.8220.
2. Polynomial Regression: Achieved an R² Score of -0.02611 and an MSE of 0.8324.
3. Ridge Regression: Achieved an R² Score of -0.00065 and an MSE of 0.8220.
4. Lasso Regression: Achieved an R² Score of -0.0000267 and an MSE of 0.8217.

Classification Models
1. Decision Tree Classifier: Achieved an accuracy of 31.7%.
2. Logistic Regression: Achieved an accuracy of 34.2%.
3. K-Nearest Neighbors (KNN) Classifier: Achieved an accuracy of 33.6%.
4. Support Vector Classifier (SVC): Achieved an accuracy of 31.35%.
5. vGaussian Naive Bayes: Achieved an accuracy of 32.3%.

Key Learning Outcomes:

--> Hands-on experience with full ML pipeline

--> Understanding of preprocessing tools (one-hot encoding, feature scaling)

--> Comparison of multiple algorithms on the same dataset

--> Ability to make predictions on new/unseen data

--> Insight into why certain models perform poorly or well on specific datasets
