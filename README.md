# twitter_sentiment_analysis

## Overview
This is a sentiment analysis project that aims to predict the sentiment of Twitter messages about different entities. The dataset used in this project contains messages along with their corresponding sentiments, categorized as Positive, Negative, or Neutral. The main objective is to build a machine learning model that can accurately classify the sentiment of new messages.

## Dataset
The dataset consists of two CSV files:

twitter_training.csv: This file contains the training data used to train the sentiment analysis model.
twitter_validation.csv: This file contains the validation data used to evaluate the performance of the trained model.

## Usage
Data Preparation:

Place the twitter_training.csv and twitter_validation.csv files in the data directory.
Run the Jupyter Notebook data_preparation.ipynb to load and preprocess the data.
Model Training:

Run the Jupyter Notebook model_training.ipynb to train the sentiment analysis model using logistic regression.
The notebook performs hyperparameter tuning using GridSearchCV to find the best model.
Model Evaluation:

The trained model's performance is evaluated on the validation set using top-1 classification accuracy.
Model Deployment:

The best-trained model is used to predict the sentiment of new messages.
New messages should be preprocessed and represented as TF-IDF vectors before prediction.

## Results
The trained sentiment analysis model achieved a top-1 classification accuracy of approximately XX% on the validation set. The model effectively classifies the sentiments of new messages as Positive, Negative, or Neutral.

