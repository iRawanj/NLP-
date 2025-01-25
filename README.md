Arabic Sentiment Analysis Project
📋 Overview
This project focuses on sentiment analysis of Arabic reviews using Natural Language Processing (NLP) techniques. It leverages machine learning and deep learning models to classify Arabic reviews into three categories: positive, negative, or mixed. The primary goal is to enhance the understanding and processing of Arabic texts, despite their linguistic and cultural complexities.

📂 Dataset
Source: Kaggle (Arabic 100k Reviews)
Description: The dataset contains 100,000 Arabic reviews across various domains (hotels, movies, products, books, airlines).
Preprocessing Steps:
Stop word removal
Tokenization
Stemming
Balanced classes: 33,333 samples for each sentiment category
🛠 Approach
1. Feature Representation
Bag of Words (BoW): Extracts features based on word frequency.
TF-IDF: Highlights important terms with higher weights for rare words.
Word Embedding: Dense vector representations to capture semantic relationships.
2. Models Used
Machine Learning:
Logistic Regression
Multinomial Naive Bayes (MultinomialNB)
Deep Learning:
LSTM (Long Short-Term Memory)
3. Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
🚀 Results
Logistic Regression performed better than MultinomialNB (Accuracy: 64% vs. 62%).
LSTM achieved the highest accuracy of 66%, despite overfitting challenges.
