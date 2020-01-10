# Sentiment-Analysis
Sentiment analysis on Movie reviews on IMDB dataset from kaggle

This dataset from kaggle has 50,000 movie reviews with two columns "Reviews" and "Sentiment"(positiive or negative)
I use 40,000 rows for training and 10,000 for testing the model

1: Remove unwanted text by pre-processing 
2: Turn categorical data: Sentiment(Positive|Negative) to integer variables
3: Use Stemmer and Lemmatizer to simplify words
4: Feature Extraction with CountVectorizer/TfidfVectorizer
5: Predict with different ML algorithms(LinearSVC,Naive Bayes)

Accuracy :89.6
