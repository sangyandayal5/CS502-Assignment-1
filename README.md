# SVM Analysis and Visualization on the Wine Dataset
This project provides a comprehensive, end-to-end analysis of the classic Wine dataset using a Support Vector Machine (SVM) classifier. The Python script walks through every step of a typical machine learning workflow, from data exploration and visualization to feature engineering, hyperparameter tuning, and model evaluation.

## Project Overview
The primary goal of this project is to build an accurate model to classify different types of wine based on their chemical properties. It serves as a detailed educational example of how to apply SVMs to a real-world multi-class classification problem.

The script performs the following key tasks:

#### Data Loading & Initial Exploration: 
Loads the dataset and provides a statistical summary.

#### Exploratory Data Analysis (EDA): 
Creates various visualizations to understand feature distributions, correlations, and relationships with the target variable.

#### Feature Engineering:
Demonstrates how to create a new feature from existing ones.

#### Data Preprocessing: 
Splits and scales the data, which is a crucial step for SVM performance.

#### Hyperparameter Tuning:
Uses GridSearchCV to systematically find the optimal SVM parameters (C, gamma, and kernel).

#### Model Training & Evaluation: 
Trains the best SVM model and evaluates its performance using metrics like accuracy, a classification report, and a confusion matrix.

#### Decision Boundary Visualization: 
Reduces the data's dimensionality using PCA to visualize the SVM decision boundaries in 2D.

## About the Dataset
The analysis is performed on the Wine recognition dataset, which is sourced from the UCI Machine Learning Repository and is readily available in scikit-learn.

#### Objective:
Classify wine samples into one of three cultivars.

#### Classes: 
class_0, class_1, class_2
#### Features: 
13 numerical features representing the chemical analysis of the wines (e.g., alcohol, malic_acid, color_intensity).

