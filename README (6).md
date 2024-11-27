# Resume Classification Model

This project demonstrates a machine learning pipeline for classifying resumes. The model goes through stages of data loading, text preprocessing, feature extraction, and model building, culminating in model evaluation and interpretation.

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Text Preprocessing](#text-preprocessing)
4. [Feature Extraction](#feature-extraction)
5. [Model Building](#model-building)
6. [Model Evaluation and Interpretation](#model-evaluation-and-interpretation)
7. [Installation](#installation)
8. [Usage](#usage)

## Overview

The *Resume Classification Model* classifies documents into categories such as "Resume" or "Non-Resume" based on the content. The model leverages machine learning techniques and natural language processing (NLP) to extract relevant features and predict categories.

## Dataset

The dataset consists of text documents, which are either resumes or other types of documents. Each document is labeled as Resume or Non-Resume.

### Data Loading and Exploration

1. *Load the data*: The text documents are loaded into a pandas DataFrame.
2. *Display the first 5 documents*: The first 5 rows of the DataFrame are displayed to understand the structure of the data.
3. *Check for missing values*: The dataset is checked for missing values, and any missing data is handled appropriately.

## Text Preprocessing

1. *Clean the text data*: Text is standardized by removing unnecessary characters, converting all text to lowercase, and performing other cleaning tasks.
2. *Tokenize the text*: The text is broken down into individual words or tokens.
3. *Lemmatization/Stemming*: Words are reduced to their base or root form using either lemmatization or stemming.

## Feature Extraction

1. *Convert text to numerical features*: Text is transformed into numerical vectors using techniques like TF-IDF or word embeddings.
2. *Display the feature matrix*: The feature matrix is presented, giving a brief description of the matrix.

## Model Building

1. *Split the dataset*: The dataset is split into training and testing sets (e.g., 80% for training and 20% for testing).
2. *Train a classification model*: A machine learning classification model (e.g., Logistic Regression, Naive Bayes, SVM, Random Forest) is trained to distinguish between resumes and non-resumes.
3. *Evaluate the model*: The model's performance is assessed using standard metrics like accuracy, precision, recall, and F1-score.

## Model Evaluation and Interpretation

1. *Plot the confusion matrix*: A confusion matrix is generated to evaluate the classification performance.
2. *ROC curve and AUC*: The ROC curve is plotted, and the Area Under the Curve (AUC) is calculated to evaluate the trade-off between true positive rate and false positive rate.
