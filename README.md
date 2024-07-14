# Credit_card_fraud_detaction

# Objective
Predict whether a transaction is fraudulent based on input features using various classification algorithms.

# Dataset
Features include transaction amount, time, and anonymized variables. The dataset is highly imbalanced, with very few fraudulent transactions compared to non-fraudulent ones.

# Methodology
# Data Preprocessing:

 Handling Imbalance: Used undersampling to balance the dataset by reducing the number of non-fraudulent transactions.

Feature Scaling: Standardized the features for consistent model performance.

# Model Implementation:

Logistic Regression: A linear model used for binary classification.Estimates the probability that a given input point belongs to a certain class.
Uses the logistic function to constrain output between 0 and 1.A linear model for binary classification, predicting the probability of fraud.

DecisionTree Classifier: A non-linear model that splits the data into branches to make decisions.Each node represents a feature, each branch represents a decision 
rule, and each leaf represents an outcome.Can handle both numerical and categorical data.A tree-based model that splits data based on feature values, creating decision nodes and leaves.

Bagging Classifier: An ensemble method that combines the predictions of multiple models (typically decision trees).Reduces variance and helps prevent overfitting.
Each model is trained on a random subset of the data.An ensemble method using multiple decision trees to improve stability and accuracy.

RandomForest Classifier:An ensemble method using multiple decision trees.Each tree is built from a random subset of the data and features.Aggregates the predictions of all trees for a final prediction.Provides improved accuracy and control over overfitting. An advanced ensemble method building multiple decision trees and aggregating their predictions.

XGBoost Classifier:An implementation of gradient boosted decision trees.Sequentially builds trees, where each tree corrects the errors of the previous one.
Highly efficient and often provides superior performance.Incorporates regularization to prevent overfitting. A gradient boosting algorithm that builds an ensemble of trees in a sequential manner, optimizing performance iteratively.

# Model Evaluation:

Split data into training and testing sets.

Evaluated models using Accuracy, Precision, Recall, F1-Score, and AUC-ROC.

# Results
Logistic Regression was the best model, offering the highest F1-Score and AUC-ROC, making it effective for this imbalanced dataset.

# Conclusion
Logistic Regression was identified as the most suitable model due to its simplicity and performance in handling the imbalanced dataset.

