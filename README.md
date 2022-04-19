# Sentiment-Analysis

The project is done by Laura Jansen-Storbacka and I-fan Lin.

This is an project in the textmining course. We are given data of tweets and corresponded feeling (labels: negative, neutral, and positive). We are free to choose any models. We applied both Naive Bayes and LSTM models to predict a label on a given tweet.

In the Naive Bayes, we transform tweets into bag of words as input. In LSTM, we applied word ebeddings, either learnt from the model or directly use the word2vec.

# Code

The source codes are provided. We used the NLK modules such as space and gensim. Also, the sklearn and tensorflow modules are applied.

# Result
The LSTM models performed slightly better than Naïve Bayes accuracy.

# Source
Data: semeval-2017-tweets_Subtask-A

Paper: Rosenthal_2017_SemEval-2017 Task 4- Sentiment Analysis in Twitter
