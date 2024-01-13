# Sentiment Analysis of a movie review

This repository contains a Python script for sentiment analysis on IMDb movie reviews using a Random Forest Classifier.

## Dataset

The dataset (`IMDB Dataset.csv`) consists of movie reviews along with their sentiments (positive or negative). 
link: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

### Data Statistics

- Number of reviews: {50000}
- Number of positive reviews: {25000}
- Number of negative reviews: {25000}
- Null values: {0}
- Duplicate entries: {418}

## Data Preprocessing

The following preprocessing steps were performed on the dataset:

1. Removed the null values from reviews.
2. Removed HTML tags from reviews.
3. Converted all words to lowercase.
4. Removed stopwords.

## Model Training

A Random Forest Classifier and Gaussian NB model was trained using the Bag-of-Words (BoW) representation with a maximum of 10,000 features.

### Model Evaluation

The model achieved an accuracy of {86}% on the test set using the Random forest classifier.
