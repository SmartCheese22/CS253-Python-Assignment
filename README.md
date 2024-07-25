# [State Election Winner Classification](https://github.com/SmartCheese22/CS253-Python-Assignment/blob/main/cs253-python-assignment.ipynb)

## Overview

Classification is a fundamental machine learning task that involves categorizing data into predefined classes. In this assignment, we were provided with a dataset containing recent State and UT election winners across India. The objective is to predict the education level of the winners based on various features, utilizing multi-class classification techniques.

## Dataset

- **Source**: Election Commission of India
- **Features**: 
  - `ID`: Unique identifier for each record
  - `Candidate`: Name of the candidate
  - `Constituency ∇`: Constituency where the election was held
  - `Party`: The political party of the candidate
  - `Criminal Case`: Number of criminal cases against the candidate
  - `Total Assets`: Total assets declared by the candidate
  - `Liabilities`: Liabilities declared by the candidate
  - `state`: State or UT where the election was held
  - `Education`: Education level of the candidate (target variable)

## Task

We were required to train a machine learning model to perform multi-class classification, predicting the education level of the election winners based on the provided features while being restricted to using classical machine learning models only (e.g., SVM, KNN, Decision Tree, Random Forest).

## Steps

1. **Data Preprocessing**:
   - Handled missing values and converted categorical features to numerical values.
   - Normalized and scaled features as needed.
2. **Model Training**:
   - Split the data into training and test sets.
   - Trained various classification models (e.g., Random Forest, KNN) and evaluated their performance using the F1-score.
   - Optimized model hyperparameters using grid search and other methods.
3. **Data Visualization**:
   - Ploted the distribution of candidates with criminal records by party.
   - Visualized the wealth distribution of candidates.
