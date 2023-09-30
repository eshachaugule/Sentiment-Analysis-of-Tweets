# Sentiment-Analysis-of-Tweets

This project aims at sentiment analysis of tweets using live tweets from Twitter’s API. The API had thousands of tweets coming in every second, most of which include slang or abbreviations not easily understood by a machine as well as special characters that need to be cleaned. I used Word2Vec embedding to remove words with low similarity scores and Latent Dirichlet Allocation (LDA) for topic modeling to exclude off-topic tweets. I vectorized the data and implemented various classification algorithms to compare accuracy, precision, recall and F1 score.
