# Titanic Survival Prediction: An End-to-End Analysis

## Introduction
This repository provides a comprehensive analysis and solution to the Titanic survival prediction challenge. The notebook is designed to be beginner-friendly, with clear explanations of each step, avoiding complex technical terms where possible. Additionally, it introduces fundamental data science concepts and terminologies in a simple manner.

## Problem Statement
The goal of this project is to predict the survival of passengers aboard the Titanic based on various features. The objective is to train a machine learning model that can learn the relationship between these features and the survival outcome, and then make predictions on unseen data. This is a classic binary classification problem in machine learning, where the outcomes are classified as either survival or non-survival.

## Evaluation Metric
The performance of the model is evaluated using accuracy, which measures the percentage of correct predictions on the test data. Accuracy is calculated as the ratio of correctly predicted instances to the total instances in the dataset.

## Data Description
The dataset includes several features that may influence the survival of passengers. Below is a brief description of each feature:

-Survival: Indicator of survival (0 = Did not survive, 1 = Survived).
<br>
-Pclass: Passenger’s class (1 = First class, 2 = Second class, 3 = Third class), which also serves as a proxy for socio-economic status.
<br>
-Sex: Gender of the passenger (male or female).
<br>
-Age: Age of the passenger in years; fractions for those less than 1 year old.
<br>
-SibSp: Number of siblings or spouses aboard the Titanic.
<br>
-Parch: Number of parents or children aboard the Titanic.
-Ticket: Ticket number assigned to the passenger.
-Fare: The fare paid by the passenger.
-Cabin: Cabin number assigned to the passenger.
-Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Exploratory Data Analysis (EDA)
The EDA involves visualizing and analyzing the distribution of features such as Age, Fare, Pclass, and Sex, among others. Key insights include:

-Age Distribution: Compared before and after handling missing values.
-Gender vs. Survival: Explored the impact of gender on survival.
-Pclass vs. Survival: Analyzed survival rates across different passenger classes.
-Travel Alone vs. Survival: Created a new feature indicating if a passenger traveled alone, and studied its influence on survival.
-The analysis uses various visualization techniques, including histograms, density plots, and bar plots, to identify patterns and relationships between features and survival.

## Modeling
The project implements two machine learning models from scratch:

### Logistic Regression:

Used to predict survival based on features like Pclass, Age, Fare, Sex, and Embarked.
The model is trained using gradient descent, with a custom implementation that iteratively updates weights to minimize the loss function.


### Naive Bayes:

A probabilistic model that calculates the likelihood of survival given the observed features.
The model combines prior and conditional probabilities to make predictions.
Results
The models are evaluated based on their accuracy. Logistic regression shows promising results, while Naive Bayes provides a good baseline for comparison. Further improvements could be made through feature engineering and hyperparameter tuning.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the license. 


