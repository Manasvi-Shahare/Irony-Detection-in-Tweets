# Irony-Detection-in-Tweets

To classify text as ironic or non-ironic and study the performance of various machine learning algorithms for determining irony from English texts in tweets using natural language processing.


## Main Goal


1. Identifying different patterns and features that give an indication of irony in tweets.
2. Learning various machine learning models that classifies new tweets and calculating the accuracy of these models.
3. An important sub goal we have is to get hold of good quality data that enables us to reach our main goal.

## The Dataset

1. The dataset consists of 3834 tweets as a total. The used dataset in this assignment is the one provided in SemEval-2018 task 3.
2 .Format :- The dataset consists of 3834 tweets as a total. 1923 tweets are classified as Non-Ironic.
1911 tweets are classified as Ironic.
There are 3 attributes, separated by 1 tab, that are in the following order:
1. Tweet Index
2. Label
   1 - Ironic
   0 - Non-Ironic
3. Tweet text

## Text Preprocessing
To generate good results and lessen the number of unneeded computations, the tweets are filtered according to certain criteria.
Tokenization
Stop Words
Stemming and Lemmatization

## Extracting Features
1. Bag of Words
2. Sentiment Analysis
3. Word Embedding

## Supervised Learning
Using the sklearn library, four models are used to test the features
1. Naive Bayes Classifier
2. SVM
3. Random Forest
4. K-Nearest Neighbor Classifier
