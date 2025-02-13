# Cancer_Prediction
Using various algorithms to compare performance
# Overview
This project implements a machine learning pipeline to predict cancer diagnoses based on medical features. The dataset undergoes preprocessing, feature scaling, and classification using multiple models to identify the best-performing one.
# Features
Data Cleaning: Removes unnecessary columns and ensures consistent formatting.
Encoding: Converts categorical variables into numerical values.
Feature Scaling: Uses StandardScaler to normalize features.
Model Training & Evaluation: Implements Logistic Regression, Random Forest, SVM, and KNN models.
Performance Metrics: Evaluates models using accuracy, classification reports, and confusion matrices.
Best Model Selection: Identifies the highest-performing model based on accuracy.
# Dataset
The dataset should be in CSV format with a diagnosis column as the target variable.
# Features include various medical measurements.
Requirements
Install dependencies using:
pip install pandas numpy seaborn matplotlib scikit-learn
# Steps Followed
    Data Preprocessing
        Loaded and inspected the dataset.
        Cleaned column names and removed unnecessary columns.
        Encoded the categorical diagnosis column using Label Encoding.
        Standardized numerical features using StandardScaler.
    Model Training & Evaluation
        Split the data into training and testing sets (80-20 split).
        Trained four classification models:
            Logistic Regression
            Random Forest
            Support Vector Machine (SVM)
            K-Nearest Neighbors (KNN)
        Evaluated model performance using accuracy, classification reports, and confusion matrices.
# Results
The script trains multiple models and outputs accuracy scores, classification reports, and confusion matrices for evaluation.
# Conclusion 
After evaluating all models, Logistic Regression achieved the highest accuracy and balanced performance across precision, recall, and F1-score. This suggests that a linear decision boundary is effective for this dataset, making Logistic Regression the best-performing model for breast cancer prediction.



