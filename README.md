# Breast Cancer Classification Project using Machine Learning

## Table of Contents

1. [Problem Statement](#problem-statement)
2. [Business Goal](#business-goal)
3. [Dataset](#dataset)
4. [Dataset Information](#dataset-information)
5. [Project Pipeline](#project-pipeline)
    - [Importing Libraries](#importing-libraries)
    - [Data Reading](#data-reading)
    - [Data Preprocessing and Cleaning](#data-preprocessing-and-cleaning)
    - [Data Exploration and Visualization](#data-exploration-and-visualization)
    - [Data Correlation Analysis](#data-correlation-analysis)
    - [Data Modeling and Model Training](#data-modeling-and-model-training)
    - [Model Creation](#model-creation)
6. [Technology Used](#technology-used)

## Problem Statement

The current diagnostic process for breast cancer faces challenges in accuracy, efficiency, and subjectivity. Manual interpretation of mammograms is time-consuming and prone to variability among healthcare professionals. This project seeks to address these issues by leveraging machine learning to enhance diagnostic accuracy, automate analysis for timely results, utilize advanced imaging features, standardize diagnoses, and seamlessly integrate the classification system into existing clinical workflows. The goal is to provide a more reliable and efficient approach to breast cancer diagnosis, improving patient outcomes and overcoming current limitations in the field.

## Business Goal

The primary business goal of this project is to develop and deploy a cutting-edge machine learning-based breast cancer classification system that significantly improves the accuracy and efficiency of diagnostic processes. By providing healthcare professionals with a reliable and standardized tool, the aim is to enhance early detection, reduce diagnostic variability, and contribute to improved patient outcomes.

## Dataset

[Breast Cancer Dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)  
Binary Classification Prediction for the type of Breast Cancer.

## Dataset Information

Breast cancer is the most common cancer amongst women globally, accounting for 25% of all cancer cases. It affected over 2.1 million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumors that can be seen via X-ray or felt as lumps in the breast area. The key challenge is how to classify tumors into malignant (cancerous) or benign (non-cancerous). This project analyzes classifying these tumors using machine learning (with SVMs) and the Breast Cancer Wisconsin (Diagnostic) Dataset.

## Project Pipeline

### Importing Libraries
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Joblib

### Data Reading
- Importing Wisconsin Breast Cancer Classification data from Kaggle.
- Displaying dataset information.
- Checking the first and last 5 rows, as well as min, max, and count values.

### Data Preprocessing and Cleaning
- Converting the diagnosis column from string to integer (0 and 1).
- Changing the datatype of the column to int64.

### Data Exploration and Visualization
- Explore benign and malignant tumor percentages in a pie chart.
- Create a new DataFrame (`df`) and save the data to it.
- Checking for any NaN values.

### Data Correlation Analysis
- Finding dataset correlations.
- Plotting a heatmap to visualize correlations.
- Creating a pair plot of the first 5 columns.

### Data Modeling and Model Training
- Creating `x` and `y` variables from the dataset.
- Training the dataset using Logistic Regression, Random Forest Classifier, and Decision Tree Classifier.
- Comparing metrics and selecting the best model.
- Training the selected model on the entire dataset.

### Model Creation
- Creating a breast cancer classification model using the Joblib function.
- Loading the trained logistic regression model.

## Technology Used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Joblib
