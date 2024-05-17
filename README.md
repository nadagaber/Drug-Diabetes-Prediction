# Drug-Diabetes-Prediction

## Predicting Medication and Diagnosing Diabetes with Machine Learning

<br>

## Repository Overview:

This repository contains the implementation of two machine learning experiments aimed at predicting appropriate medication for patients and diagnosing diabetes. The experiments involve decision trees using Scikit-learn and a custom implementation of the k-Nearest Neighbors (kNN) algorithm in Python. The dataset Drug.csv is used for the decision tree experiments, while the dataset diabetes.csv is used for the kNN algorithm.

<br>

## Contents
Data Preprocessing:

Handling missing data by counting and replacing them.

Encoding categorical variables for machine learning algorithms.

<br>

Decision Trees using Scikit-learn:

First Experiment: Training and testing with fixed train-test split ratio.

Second Experiment: Training and testing with a range of train-test split ratios.

Reporting model sizes, accuracies, and comparing results to select the best model.

Generating plots for accuracy and tree size against training set size.

<br>

k-Nearest Neighbors (kNN) Algorithm:

Implementing a custom kNN classifier from scratch.

Normalizing features using Log Transformation or Min-Max Scaling.

Breaking ties using Distance-Weighted Voting.

Reporting accuracy for different k values and calculating average accuracy.
