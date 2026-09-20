# Day 4 – Machine Learning: Facility Hygiene Risk Prediction

## Project Overview

This project focuses on predicting the hygiene risk level of a facility using machine learning classification algorithms.

The target variable `hygiene_risk` contains three categories:

* Low
* Medium
* High

Two machine learning algorithms were trained and evaluated to compare their performance.

## Objective

To predict the hygiene risk of a facility using factors related to cleanliness, waste, complaints, footfall, and cleaning frequency.

## Features Used

* cleanliness_score
* odor_score
* waste_level
* complaints
* footfall
* hours_since_cleaning

Target: hygiene_risk

## Workflow

1. Dataset Loading
2. Data Cleaning and Validation
3. Exploratory Data Analysis
4. Feature Selection
5. Train-Test Split
6. Model Training
7. Prediction
8. Model Evaluation
9. Confusion Matrix Analysis
10. Model Comparison

## Models Used

### Logistic Regression

Accuracy: 88.44%
Precision: 88.59%
Recall: 88.44%
F1 Score: 88.47%

### Decision Tree

Accuracy: 80.90%
Precision: 81.49%
Recall: 80.90%
F1 Score: 80.99%

## Model Comparison

Logistic Regression achieved higher Accuracy, Precision, Recall, and F1 Score than the Decision Tree on the test dataset.

Therefore, Logistic Regression was selected as the final model for this project.

## Dataset Information

The dataset contains 995 records and 12 columns.

Hygiene Risk Distribution:

Medium: 410
Low: 313
High: 272

No missing values or duplicate records were found during data validation.

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

## Possible Improvements

* Hyperparameter tuning
* Cross-validation
* Testing additional machine learning algorithms
* Feature engineering
* Adding more relevant features
* Deploying the model as a web application or API

## Technologies Used

Python
Pandas
NumPy
Scikit-learn
Jupyter Notebook
Machine Learning
Classification

