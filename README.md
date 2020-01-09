# Word2Vec-and-Doc2Vec-Sentiment-Analysis-
In this project, performed sentiment analysis over IMDB movie reviews and Twitter data

Goal was to classify tweets or movie reviews as either positive or negative. 

Towards the end, used labeled training to build the model and labeled testing data to evaluate the model. For classification, experimented with logistic regression as well as a Naive Bayes classifier from python’s well-regarded machine learning package scikit-learn. 

As a point of reference, Stanfords Recursive Neural Network code produced an accuracy of 51.1% on the IMDB dataset and 59.4% on the Twitter data. 

A major part of this project is the task of generating feature vectors for use in these classifiers. 

Explored two methods: 

(1) A more traditional NLP technique where the features are simply “important” words and the feature vectors are simple binary vectors and 
(2) the Doc2Vec technique where document vectors are learned via artificial neural networks 
