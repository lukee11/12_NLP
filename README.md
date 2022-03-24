# Unit 12 Tales from the Crypto

![Stock Sentiment](Images/sentimental.jpeg)

## Background

in this repository, I used natural language processing to decipher the emotion in recent news stories about Bitcoin and Ethereum. I also applied  NLP techniques to better understand the other aspects that influence coin pricing, such as common terms and phrases, as well as the businesses and entities mentioned in the articles.

Completed tasks:
1. [Sentiment Analysis](#1---Sentiment-Analysis)
2. [Natural Language Processing](#2---Natural-Language-Processing)
3. [Named Entity Recognition](#3---Named-Entity-Recognition)

---

## Files

[Crypto Sentiment Notebook](My_Code/crypto_sentiment.ipynb)

---

### 1 - Sentiment Analysis

![ETH_title text comparison](Images/eth_comparison.PNG)

### Questions:

*Q: Which coin had the highest mean positive score?*

A: Bitcoin had the highest title_pos mean of 0.081.

*Q: Which coin had the highest compound score?*

A: Ethereum has the highest title_compund score of 0.459.

*Q. Which coin had the highest positive score?*

A: Ethereum has the highest title_pos score of 0.250.

Note: I used title for all questions as it has more context to the brief.


### 2 - Natural Language Processing

#### ETHEREUM N-grams Counter 
![BTC N-grams](Images/btc_n-grams.PNG)

#### Word Clouds

![btc-word-cloud.png](Images/btc_WC.PNG)

![eth-word-cloud.png](Images/eth_WC.PNG)


### 3 - Named Entity Recognition

![btc-ner.png](Images/btc_NER.PNG)

- - - 

### Resources

[Vader Sentiment Analysis](http://www.nltk.org/howto/sentiment.html)

- - - 

### Built With

* python

* pandas

* nltk

* newsapi

* matplotlib

* wordcloud

* spacy

- - - 