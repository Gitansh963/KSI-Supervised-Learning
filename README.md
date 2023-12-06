# KSI Dataset Project

KSI Dataset Project is a supervised learning project that aims to predict the severity of traffic collisions in Toronto based on various features. The project uses the KSI dataset from the City of Toronto Open Data Portal, which contains information on traffic collisions that resulted in fatalities or injuries from 2008 to 2019.

## Features

- Data exploration and visualization using pandas, matplotlib, and seaborn
- Data preprocessing and transformation using sklearn and custom functions
- Data splitting and scaling using train_test_split and StandardScaler
- Model selection and evaluation using cross-validation, grid search, and various metrics
- Model comparison and selection using confusion matrix, classification report, accuracy score, and ROC curve
- Model deployment and persistence using joblib
- Frontend development using flask and HTML/CSS

## Models

The project compares and selects from the following models:

- Support Vector Classifier (SVC)
- Decision Tree Classifier
- Logistic Regression
- Random Forest Classifier
- Bernoulli Naive Bayes
- Multilayer Perceptron Classifier (MLPClassifier)

## Installation

To run this project, you need to have Python 3 and the following libraries installed on your machine:

- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- flask
- joblib

You also need to download the KSI dataset from the City of Toronto Open Data Portal and place it in the data folder of the project.

## Usage

To use this project, you need to run the main.py file, which will launch the flask app on your local server. Then, you can access the app on your browser and enter the values for the features that you want to predict the severity of the collision. The app will display the prediction and the probability of each class.
