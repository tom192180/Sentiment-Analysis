# Sentiment-Analysis

The project is done by Laura Jansen-Storbacka and I-fan Lin

This is an project in the textmining course. We are given tweets and corresponded feeling (labels: negative, neutral, and positive) and we are free to choose any models. We applied both Naive Bayes and LSTM models to predict a label on a given tweet.

In the Naive Bayes, we transform tweets into bag of words as input. In LSTM, we applied word ebeddings, either learnt from the model or word2vec.

# Code

The source code is not provided because it takes extra time to organize, but basically we use NLP modules such as gensim and spacy. Also, tensorflow and scikit-learn are used for modeling.   

# Result
The LSTM models performed slightly better than Naïve Bayes accuracy.

# Source
Data: semeval-2017-tweets_Subtask-A
Paper: Rosenthal_2017_SemEval-2017 Task 4- Sentiment Analysis in Twitter
