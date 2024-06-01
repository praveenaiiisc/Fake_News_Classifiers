# Fake_News_Classifiers
* Build a system to identify unreliable news articles
## Data
* train.csv: A full training dataset with the following attributes:

    id: unique id for a news article
    title: the title of a news article
    author: author of the news article
    text: the text of the article; could be incomplete
    label: a label that marks the article as potentially unreliable
    1: unreliable
    0: reliable
* test.csv: A testing training dataset with all the same attributes at train.csv without the label.
## Method 1
* Creating the Bag of Words and Implement Classfier using 2 methods:
   1. MultinomialNB Algorithm and set Hyperparameter,
   2. Using Passive Aggressive Classifier Algorithm
* Creating the TF_IDF abd again Implement Classfier using 2 methods
## Method 2
* Fake News Classifier Using LSTM and increse the Accuracy
