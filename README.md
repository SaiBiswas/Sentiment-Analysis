## Sentiment-Analysis

Sentiment analysis remains one of the key problems that has seen extensive application of natural language processing. 
We are given the tweets from customers about various tech firms who manufacture and sell mobiles, computers, 
laptops, etc, the task is to identify if the tweets have a negative sentiment towards such companies or products.
We will work on this problem and then classify the tweets as positive or negetive sentiment.


## EDA Steps taken

The following steps are taken in the Exploratory Data Analysis:
1. Checking the number of positive sentiments in the tweet data.
2. Checking the number of negetive sentiments in the tweet data.
3. Checking the distribution of the label count.
4. Checking the distribution of the tweet in both the test and train data.


## Preprocessing the Data

1. Count Vectorization of the tweet data.
2. Checking the 30 most frequently occuring words in the tweets.
3. Checking the number of hashtags in the train data and test data.
4. Extracting the number of hashtags in the train and test data.
5. Checking the most frequent occuring words in the data.
6. Tokenizing the words present in the train and text data.
7. Using Gensim for checking the most similar occuring words in the data.
8. Creating a bag of words for the  whole tweets data.
9. Standardizing the whole tweets data.

## Machine Learning Modelling

1. Random Forest giving a F1 score of 79.2% on test data.
2. SVM (Support Vector Machines) giving a F1 score of 70% on the test data.
3. XG Boost Classification giving a F1 score of 72.2% on the test data.
4. Logistic Regression giving a F1 score of 68.97% on the test data.
5  Decision Tree algorithm giving an F1 score of 70.1 % on test data.

So, amongst all the algos, We will select the Random Forest Model as it has the highest F1 score on unseen data.
