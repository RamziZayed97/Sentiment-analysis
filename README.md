# Sentiment-analysis
Overview
This project implements sentiment analysis and emotion detection using logistic regression. It preprocesses text data from CSV files (train.csv, test.csv, val.csv), removes stopwords, and applies TF-IDF vectorization. The trained model predicts sentiment labels: positive, negative, and neutral, as well as six primary emotions—joy, sadness, anger, fear, surprise, and disgust.

Usage
Data Preprocessing: Clean and preprocess text data.
Model Training: Train a logistic regression model with TF-IDF features.
Evaluation: Assess model performance on validation and test sets.
Prediction: Predict sentiment labels and emotions for new text inputs.
Dependencies
Python 3.x
Libraries: pandas, nltk, scikit-learn, matplotlib, wordcloud
