#Sentiment Analysis with Machine Learning
This is a simple sentiment analysis project that uses machine learning to classify the sentiment of movie reviews as positive or negative. The project is implemented in Python and uses the scikit-learn library for machine learning and the IMDb movie review dataset for training and testing the model.

#Dataset
The IMDb movie review dataset is a popular dataset for sentiment analysis tasks. It contains a set of 50,000 movie reviews, evenly split into 25,000 training and 25,000 testing samples. Each review is labeled as either positive or negative based on the overall sentiment expressed in the review.

The IMDb movie review dataset can be downloaded from [this link](https://ai.stanford.edu/~amaas/data/sentiment/).

#Model
The sentiment analysis model in this project uses a simple bag-of-words approach for feature extraction and a Naive Bayes classifier for prediction. The bag-of-words model represents each document as a vector of word frequencies, where each element of the vector corresponds to the frequency of a specific word in the document. The Naive Bayes classifier is a probabilistic classifier that estimates the probability of each class given the observed feature values.
