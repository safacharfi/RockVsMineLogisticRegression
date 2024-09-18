# RockVsMinePrediction

This repository contains a Jupyter Notebook project for predicting rock versus mine using a logistic regression model on the `sonar.csv` dataset.

## Project Overview

The goal of this project is to build and evaluate a logistic regression model to classify sonar readings into two categories: rock or mine. The `sonar.csv` dataset contains sonar readings and their corresponding labels. 

## Dataset

The dataset used in this project is `sonar.csv`. It consists of sonar readings from a sonar device, with the following structure:

- **Features:** 60 numerical features representing sonar readings.
- **Label:** A binary label indicating whether the reading corresponds to a rock or a mine.

## Getting Started

### Prerequisites

Make sure you have the following Python libraries installed:

- `numpy`
- `pandas`
- `scikit-learn`

You can install these libraries using pip:

```bash
pip install numpy pandas scikit-learn
```



## Logistic Regression Model

### Description

Logistic Regression is a statistical method for binary classification. It predicts the probability of a binary outcome (0 or 1) based on one or more predictor variables. The logistic regression model outputs probabilities using the logistic function, and these probabilities are used to classify data points into one of the two classes.

### Key Steps

1. **Data Preprocessing:**
   - Load and clean the dataset.
   - Split the data into features and labels.
   - Split the data into training and testing sets.

2. **Model Training:**
   - Initialize the `LogisticRegression` model from `sklearn`.
   - Fit the model to the training data.

3. **Model Evaluation:**
   - Predict labels for the test set.
   - Calculate the accuracy score using `accuracy_score` from `sklearn`.

