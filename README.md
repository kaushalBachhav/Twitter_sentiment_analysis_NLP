# Twitter_sentiment_analysis_NLP

## Overview

This project performs sentiment analysis on a collection of tweets. The model employs Logistic Regression to categorize tweets as **Positive** or **Negative** based on their content. 


## Dataset

The **Sentiment140 dataset** from Kaggle ([https://www.kaggle.com/kazanova/sentiment140](https://www.kaggle.com/kazanova/sentiment140)). This dataset contains 1.6 million tweets labeled as either positive or negative.

The dataset comprises the following fields:

  * `target`: Sentiment label (0 = Negative, 4 = Positive, converted to 0 and 1)
  * `id`: Unique tweet identifier
  * `date`: Timestamp of the tweet
  * `flag`: Query flag (unused in this project)
  * `user`: Username of the tweet's author
  * `text`: The actual content of the tweet

## Project Structure

The core components of this project encompass:

  * Data download from Kaggle utilizing the API
  * Data preprocessing (text cleaning and stemming)
  * Transformation of text data into numerical features using TF-IDF
  * Training a Logistic Regression model
  * Evaluation of the model's performance on training and test datasets
  * Saving the trained model with pickle for future use

