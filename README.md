# Financial news sentiment analysis
A machine learning project analyzing financial news sentiment using TF-IDF vectorization and logistic regression.

Financial News Sentiment Analysis

Introduction

This project aims to analyze the sentiment of financial news articles using Natural Language Processing (NLP) techniques. The dataset was collected using the News API and includes articles related to stock markets, finance, and fintech. The goal is to classify the sentiment of news articles as positive or negative, which can help investors and analysts gain insights into market trends.

Technologies Used

Programming Language: Python

Libraries:
  Data processing: pandas, numpy
  Text preprocessing: re
  NLP: sklearn.feature_extraction.text.TfidfVectorizer
  Machine Learning: sklearn.linear_model.LogisticRegression
  Visualization: matplotlib, seaborn
  API: News API for article collection

Steps:

  Data Collection:
    Used the News API to fetch articles based on financial keywords like "stock market," "finance," and "fintech."
  Text Preprocessing:
    Cleaned and tokenized text using regular expressions to remove special characters, numbers, and extra spaces.
  Vectorization:
    Converted text into numerical features using the TF-IDF Vectorizer.
  Modeling:
    Trained a Logistic Regression model to classify the sentiment of the articles.
  Evaluation:
    Evaluated the model using metrics like accuracy, confusion matrix, and classification report.
  Visualization:
    Plotted metrics and feature importance for better interpretability.
  
Results:

  Achieved an accuracy of 93.75% on a balanced dataset after optimizing for class imbalance using class_weight=balanced.
  Visualizations demonstrate the distribution of sentiments and the performance of the classifier.
