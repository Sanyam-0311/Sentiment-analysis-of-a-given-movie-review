# Sentiment-analysis-of-a-given-movie-review
A project made using machine learning to understand the sentiment of a review entered by the user.
# Generate the markdown content
markdown_content = """
# IMDb Sentiment Analysis

This repository contains a Python script for sentiment analysis on IMDb movie reviews using a Random Forest Classifier.

## Dataset

The dataset (`IMDB Dataset.csv`) consists of movie reviews along with their sentiments (positive or negative). 

### Data Statistics

- Number of reviews: {}
- Number of positive reviews: {}
- Number of negative reviews: {}
- Null values: {}
- Duplicate entries: {}

## Data Preprocessing

The following preprocessing steps were performed on the dataset:

1. Removed HTML tags from reviews.
2. Converted all words to lowercase.
3. Removed stopwords.

## Model Training

A Random Forest Classifier was trained using the Bag-of-Words (BoW) representation with a maximum of 10,000 features.

- Training set shape: {}
- Test set shape: {}

### Model Evaluation

The model achieved an accuracy of {}% on the test set.

Confusion Matrix:
