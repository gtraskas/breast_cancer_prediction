# Breast Cancer Analysis and Prediction

In this repository, advanced machine learning methods were used to build and test the performance of a selected algorithm for breast cancer diagnosis.

## Dataset

The Breast Cancer Wisconsin (Diagnostic) Dataset - obtained from [Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data) - contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass and describe characteristics of the cell nuclei present in the image.

## The Analysis

### Data Loading and Cleaning

Load data into pandas dataframe and "clean" them from missing and incosistent values.

### Data Exploration

Produce descriptive statistics and plots to reveal trends and relationships between the variables.

### Machine Learning

#### Split Data to Train/Test Sets

Split data into train and test data sets and use cross validation.

#### Scale Features

Standarize predictor variables with feature scaling.

#### Dimensionality Reduction

Select features with Principal Component Analysis (PCA) or `SelectKBest()`. Plot graphs to show the effect of feature scaling on PCA.

#### Tune the Algorith and Evaluate

Optimize the algorithm with `GridSearchCV` and `Pipeline`. Evaluate with recall score considering it as the most important metric.
