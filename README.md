# Sentiment Analysis of Tweets

This project focuses on performing sentiment analysis on tweets using machine learning. The objective is to classify the sentiment of a given tweet as either positive or negative. The project uses Python and popular libraries such as Pandas, Scikit-learn, and NLTK.

## Overview

This project applies machine learning algorithms to classify the sentiment of tweets. The dataset contains tweets with corresponding sentiment labels (target), and the project applies Natural Language Processing (NLP) techniques to process and analyze the tweet texts.

## Data

The data used for this project is stored in `tweet_data.csv` and contains two columns:
- **text**: The content of the tweet.
- **target**: The sentiment label (positive or negative).

## Preprocessing

The preprocessing steps applied to the tweet text include:
- **Tokenization**: Breaking down the text into individual words (tokens).
- **Removing Punctuation**: Cleaning the text by removing punctuation marks.
- **Removing Stopwords**: Filtering out common words that don't add much meaning to the sentiment (e.g., "the", "is").
- **Lemmatization**: Reducing words to their base form (e.g., "running" becomes "run").

## Modeling

In this project, the following models are used:
- **Logistic Regression**
- **Multinomial Naive Bayes**
- **Random Forest Classifier**


## Evaluation

The performance of the models is evaluated using the following metrics:
- **Accuracy**: The proportion of correct predictions.
- **Precision**: The proportion of true positive predictions among all positive predictions.
- **Recall**: The proportion of true positive predictions among all actual positives.
- **F1-score**: The harmonic mean of precision and recall.
