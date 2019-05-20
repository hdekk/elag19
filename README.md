# Repo for Making Sense of AI workshop - ELAG 2019, Berlin

The Jupyter Notebook ML_lesson.ipynb was adapted from code posted in the following article: 
[A Simple NLP Sentiment Analysis with Keras and Google Colaboratory](https://medium.com/i-a/simple-nlp-sentiment-analysis-with-google-colaboratory-761a5391b57c).

The Notebook code has been tested in [Google Colaboratory](https://colab.research.google.com) using a free account.

The data used in the lesson was posted on https://github.com/Seh83/ML_Sentiment_Label_Model and has been copied to this repo without modification. The origins of the data are described below:

-----------------------------------------------------------------------------------------------------------------------------------
This dataset was created for the Paper 'From Group to Individual Labels using Deep Features', Kotzias et. al,. KDD 2015
Please cite the paper if you want to use it :)

It contains sentences labelled with positive or negative sentiment, extracted from reviews of products, movies, and restaurants

**Format:**  
sentence \t score \n


**Details:**  
Score is either 1 (for positive) or 0 (for negative)	
The sentences come from three different websites/fields:  

imdb.com  
amazon.com  
yelp.com  
  
For each website, there exist 500 positive and 500 negative sentences. Those were selected randomly for larger datasets of reviews. 
We attempted to select sentences that have a clearly positive or negative connotaton, the goal was for no neutral sentences to be selected.



For the full datasets look:  

imdb: Maas et. al., 2011 'Learning word vectors for sentiment analysis'  
amazon: McAuley et. al., 2013 'Hidden factors and hidden topics: Understanding rating dimensions with review text'  
yelp: Yelp dataset challenge http://www.yelp.com/dataset_challenge
