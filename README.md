# Sentiment-analysis
This repository contains code and data for sentiment analysis of IMDB movie reviews using various machine learning algorithms. The dataset used for this analysis is sourced from Kaggle and can be found at the following link: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?resource=download

About dataset:
The dataset consists of 50,000 movie reviews from IMDB, split into 40,000 for training and 10,000 for testing. Each review is labeled as either positive or negative, indicating the sentiment expressed in the review. The data is provided in a CSV format, and we utilized Python's Pandas library for data manipulation and analysis.

Preprocessing:
Before feeding the data into the machine learning models, we performed preprocessing steps to clean and prepare the text data for analysis.This includes tasks such as converting text to lowercase, removing punctuation, tokenization, stopword removal, and stemming or lemmatization.

Algorithms Used:
Four different machine learning algorithms were used for sentiment analysis:

Support Vector Machine (SVM): Achieved an accuracy of 87.49%.

Naive Bayes: Achieved an accuracy of 85.08%.

Multilayer Perceptron (MLP): Achieved an accuracy of 87.07%.

Convolutional Neural Network (CNN): Achieved an accuracy of 87.48%.
