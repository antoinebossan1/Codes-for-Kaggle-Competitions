# Spaceship Titanic Survival Prediction

This project aims to compare different machine learning algorithms from scikit-learn to see which one performs the best in predicting the transportation of passengers from the spaceship Titanic (https://www.kaggle.com/competitions/spaceship-titanic). Also, the efficiency of hyperparameter tuning is analyzed by measuring the time in seconds it takes to fine-tune the best model, here XGBoost, and comparing its performance on the test dataset before and after fine-tuning. 

I am very interested in machine learning and data science, and this project serves as an opportunity for me to compare different algorithms and see which one performs the best in this classification task and explore the impact of hyperparameter tuning on model performance. The results of this analysis are presented in the 'Submission' section of this README.


1. RandomForestClassifier
2. Support Vector Machines (SVC)
3. K-Nearest Neighbors (KNN)
4. Logistic Regression
5. XGBoost

## Table of Contents

- [Introduction](#introduction)
- [Model Evaluation](#model-evaluation)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Submission](#submission)

## Introduction

The Spaceship Titanic dataset contains information about passengers, such as their age, home planet, and various services they used onboard the spaceship. The goal is to predict whether a passenger was transported or not.


## Model Evaluation

The models are evaluated based on their accuracy scores. The model with the highest accuracy score is considered the best performing model. The following models are compared:

1. RandomForestClassifier
2. Support Vector Machines (SVC)
3. K-Nearest Neighbors (KNN)
4. Logistic Regression
5. XGBoost

## Hyperparameter Tuning

The best performing model (XGBoost) is further fine-tuned using GridSearchCV for hyperparameter tuning to improve its performance.

## Submission

The final predictions are generated using the best performing and fine-tuned model. The predictions are then saved as a CSV file and submitted to the Kaggle competition. Here are the results:<img width="1210" alt="submissions" src="https://user-images.githubusercontent.com/121366737/233836115-5f6f77b2-8e7d-4343-8ace-fcfdf8a6ee3d.png"> It is observed that the accuracy improved by 0.00491 after 26 minutes of fine-tuning the model. This demonstrates the trade-off between the computational cost of hyperparameter tuning and the potential improvement in model performance.
