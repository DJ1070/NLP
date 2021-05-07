# Sentiment Detection on Twitter Tweets with Natural Language Processing (NLP) 

<img src = './photos/twitter-nlp.jpg' width = 960 height = 640>

The goal of this deep learning project is to set up an automatic detection of the sentiments of Twitter Tweets. 

I'm using a <a href = 'https://www.kaggle.com/kazanova/sentiment140?select=training.1600000.processed.noemoticon.csv'>pre-labeled dataset from Kaggle</a> with 1,6 million tweets, exactly half of them weighed positive, half negative. Even though I scraped Twitter earlier myself, I don't take that data since manual labelling and deletion of all languages but English would take too long now.

<a href = 'https://keras.io/'>Keras</a> and <a href= 'https://www.tensorflow.org/'>Tensorflow</a> are the main tools to tackle this analytical task on <a href = 'https://colab.research.google.com/'>Google Colab</a> because of Colab's computing power (if GPU is enabled). Unfortunately loading the original dataset into Colab threw a lot of errors (which my local Visual Studio Code didn'T), so the data needed some cleaning ahead.

