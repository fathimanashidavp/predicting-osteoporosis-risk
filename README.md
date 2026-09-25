# Predicting Osteoporosis Risk

## Project Overview

This project focuses on predicting osteoporosis risk using machine learning techniques. The analysis uses patient demographic, lifestyle, and health-related factors to identify patterns associated with osteoporosis and build predictive models.

## Objectives

- Explore and understand the osteoporosis dataset
- Perform data cleaning and exploratory data analysis
- Preprocess categorical and numerical features
- Train and compare multiple machine learning models
- Evaluate model performance using different metrics
- Tune the selected model to improve its performance

## Dataset

The dataset contains *1,958 records and 16 columns*.

### Target Variable

- Osteoporosis – Target variable indicating osteoporosis status

### Key Features

- Age
- Gender
- Hormonal Changes
- Family History
- Race/Ethnicity
- Body Weight
- Calcium Intake
- Vitamin D Intake
- Physical Activity
- Smoking
- Alcohol Consumption
- Medical Conditions
- Medications
- Prior Fractures

## Exploratory Data Analysis

The project includes analysis of:

- Target variable distribution
- Age distribution
- Gender distribution
- Age groups and osteoporosis status
- Family history
- Calcium and Vitamin D intake
- Physical activity
- Prior fractures
- Hormonal changes
- Race/Ethnicity
- Body weight
- Smoking
- Alcohol consumption
- Medical conditions

## Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Checked for duplicate records
- Handled missing categorical values using Unknown
- Removed the Id column from model features
- Encoded categorical variables using one-hot encoding
- Split the data into training and testing sets using stratification

## Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors (KNN)

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

## Hyperparameter Tuning

K-Nearest Neighbors was further tuned using GridSearchCV.

The best parameters obtained were:

- n_neighbors = 15
- weights = uniform
- metric = euclidean

## Final Model Performance

The tuned KNN model achieved:

| Metric | Score |
|---|---:|
| Accuracy | 85.2% |
| Precision | 99% |
| Recall | 71% |
| F1-Score | 83% |
| ROC-AUC | 87.6% |
| Cross-Validation Accuracy | 88.4% |

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Files

- Predicting_Osteoporosis_Risk.ipynb – Complete data analysis, preprocessing, model training and evaluation
- Predicting_Osteoporosis_Risk.pdf – Project presentation
- osteoporosis.csv – Dataset used for the analysis

## Conclusion

This project demonstrates the use of machine learning techniques to analyze osteoporosis-related factors and build a predictive model. Multiple models were compared, and a tuned KNN model was evaluated as the final model for the available dataset.
