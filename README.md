# Twitter Sentiment Analysis

A classical machine learning project for sentiment analysis of Twitter messages, developed as coursework for a Machine Learning course.

## Project Overview

The project uses the Stanford Twitter Sentiment Dataset to classify tweets as positive or negative.

The workflow includes:

- Text preprocessing and cleaning
- Tokenization with NLTK
- Stop-word removal
- TF-IDF feature extraction
- 80/20 train-test split
- Comparison of multiple classical ML classifiers
- Confusion matrix and classification metrics

## Models Evaluated

The following classifiers were compared:

- Multinomial Naive Bayes
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors

## Results

Logistic Regression achieved the best performance, reaching approximately **80% accuracy** on the largest evaluated dataset.

The experiments also showed that model performance varied significantly across algorithms, with KNN performing substantially worse than the other approaches.

## Dataset

The project is based on the **Stanford Twitter Sentiment Dataset**, containing approximately 1.6 million labeled tweets.

The repository does not include the original dataset.

## Technologies

- Python
- scikit-learn
- NLTK
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Context

This project was completed as part of a Machine Learning course at ITMO University.

It represents an earlier classical ML/NLP project in my portfolio and complements my more recent work in production-oriented machine learning and MLOps.
