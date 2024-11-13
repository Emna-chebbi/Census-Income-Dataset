# Census-Income-Dataset

This repository contains a Jupyter Notebook used for building and evaluating a classification model on census income data. The notebook demonstrates steps for data preprocessing, model training with a Decision Tree Classifier, Random Forest Classifier, and model evaluation.

# Overview
This project aims to classify individuals based on census income data using a machine learning model. 
The classification is intended to predict whether an individual's income is above or below a certain threshold, based on various demographic and employment features.

# Dataset
The dataset used in this project is a census income dataset. This notebook processes and trains on a dataset with the following main attributes:

Demographic Attributes: Age, education, gender, etc.
Employment Attributes: Workclass, occupation, etc.
Geographic Attributes: Native country, etc.

# Data Preprocessing

The following preprocessing steps are performed in the notebook:

Loading Data: The dataset is loaded into a Pandas DataFrame.

Handling Missing Values: Certain columns (Workclass, Occupation, Native-country) contain missing values represented by '?'. 
Rows with these values are removed to clean the data.

Data Splitting: The data is divided into training and testing sets for model training and evaluation.

# Modeling
The models used for classification are Decision Tree Classifier and Random Forest Classifier, chosen for their robustness and ability to handle a wide range of features. 
The models were trained on the cleaned dataset to classify individuals based on the provided attributes.

# Evaluation
After training, the model is evaluated using a classification report to analyze the accuracy, precision, recall, and F1 score. 
The following metrics are calculated:

Accuracy: Overall accuracy of the model.
Precision: Precision score for each class.
Recall: Recall score for each class.
F1 Score: F1 score, a weighted average of precision and recall.

