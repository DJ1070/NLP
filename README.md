# Sentiment Detection on Twitter Tweets with Natural Language Processing (NLP) 

<img src = './photos/twitter-nlp.jpg' width = 960 height = 400>

The goal of this deep learning project is to create an automatic detection of the sentiments of Twitter Tweets. 

I'm using a <a href = 'https://www.kaggle.com/kazanova/sentiment140?select=training.1600000.processed.noemoticon.csv'>pre-labeled dataset from Kaggle</a> with 1,6 million tweets, exactly half of them weighed positive, half negative. The Tweets are in English and randomly selected. Even though I scraped Twitter in a previous project myself, I don't take that data since manual labelling and deletion of all languages but English would take too long now.

<a href = 'https://www.nltk.org/'>NLTK</a>, <a href = 'https://keras.io/'>Keras</a> and <a href= 'https://www.tensorflow.org/'>Tensorflow</a> are the main tools to tackle this analytical task on <a href = 'https://colab.research.google.com/'>Google Colab</a> because of Colab's computing power (if GPU is enabled). Unfortunately loading the original dataset into Colab threw a lot of errors (which my local Visual Studio Code didn'T), so the data needed some cleaning ahead.

The steps are:
<ul>
  <li>Removing URLs, citations and e-mail addresses as well as punctuation and so called <a href = 'https://medium.com/@saitejaponugoti/stop-words-in-nlp-5b248dadad47'>stop words</a>. Stop words (I, you, between, against, for, very etc.) are widely used and don't add to understanding in NLP.</li>
  <li>Tokenization</li>
  <li>Splitting the dataset into a train and a test part with a validation set inbetween</li>
</ul>
