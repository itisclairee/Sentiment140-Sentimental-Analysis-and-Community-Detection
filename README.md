# Sentiment140-Sentimental-Analysis-and-Community-Detection

## Introduction

This project demonstrates the use of the Databricks framework to implement machine learning algorithms on big data sets. The dataset used is the Sentiment140 dataset, which is widely used for sentiment analysis tasks, sourced from Kaggle at the following link:
https://www.kaggle.com/datasets/kazanova/sentiment140/data. 
Sentiment analysis is a form of text classification within the field of Natural Language Processing (NLP), aimed at determining the sentiment expressed in a given body of text.

NLP is a branch of computer science that enables the computational analysis of human language. Recent advances in machine learning, particularly in neural networks, have significantly improved capabilities in areas such as speech recognition, natural language understanding, and text classification.

## Goals

Our goals are: 
- Utilize the Sentiment140 dataset to perform sentiment analysis.

- Implement machine learning models on Databricks to handle large-scale text data efficiently.

- Explore various NLP techniques to improve classification accuracy.


## Technologies Used

- Databricks: A cloud-based platform for big data and machine learning.

- Apache Spark: Distributed computing framework for handling large-scale data processing.

- Python: Programming language used for data processing and model training.

- MLflow: Experiment tracking and model deployment.

- scikit-learn: Machine learning library for text classification models.

- NLTK: Library for text preprocessing and NLP tasks.

## Dataset

The Sentiment140 dataset contains 1.6 million tweets annotated with sentiment labels (positive or negative). The dataset includes the following columns:

- target: Sentiment label (0 = negative, 4 = positive)

- id: Unique identifier for each tweet

- date: Timestamp of the tweet

- flag: Query-related information (not relevant for sentiment analysis)

- user: Twitter username

- text: The tweet's content

## Usage

The workflow is implemented in Databricks notebooks.

The dataset is preprocessed using NLP techniques like tokenization, stopword removal, and stemming.

Various machine learning models (Logistic Regression, Naïve Bayes, etc.) are trained and evaluated.

Results are visualized to assess model performance.



