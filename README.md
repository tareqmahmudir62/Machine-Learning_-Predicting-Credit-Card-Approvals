

# Machine-Learning_-Predicting-Credit-Card-Approvals (Building an automatic credit card approval predictor using machine learning techniques)

This is a project from DataCamp's Machine Learning courses. In this project, we explore how machine learning techniques can be applied to automate the task of credit card approval. We use the Credit Card Approval dataset from the UCI Machine Learning Repository to build an automatic credit card approval predictor.

## Introduction

In this notebook, we preprocess the dataset, explore the data, and finally build a machine learning model that can predict if an individual's application for a credit card will be accepted or not.

## Task 1: Load and Inspect the Dataset

We load and inspect the dataset to discern the essential features of a credit card application.

## Task 2: Inspecting the Application

We identify any issues that need to be resolved with the dataset.

## Task 3: Splitting the Dataset into Train and Test Sets

We prepare our data for machine learning modeling by splitting our dataset into two different sets: the training set and the test set. We drop the features that are not as important as the other features in the dataset for predicting credit card approvals.

## Task 4: Handling the Missing Values

We replace the missing values with NaN and apply the mean imputation strategy for the numerical columns. For non-numeric columns with missing values, we use the most frequent values as present in the respective columns to impute the missing values.

## Task 5: Preprocessing the Data

We convert non-numeric data to numeric and scale feature values to a uniform range.

## Task 6: Fitting a Logistic Regression Model to the Train Set

We fit a logistic regression model to the train set to predict whether a credit card application will be approved or not.

