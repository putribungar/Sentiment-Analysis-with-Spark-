# Sentiment-Analysis-with-Spark-
### by Putri Bunga Rahmalita
--------------------------------------------------------------------------------------------------
Social media is an interactive technology that allows users to share information, ideas, and other forms of expression through communities and virtual networks. With the existence of social media data is becoming more and more. However, if the data is not used, it will only become garbage. Data from social media is very useful for several aspects, for example is for sentiment analysis. 
<br><br>
Sentiment analysis is the automated process of understanding an opinion about a given subject from written language. In addition, sentiment analysis like this can be used by several companies to find out how the community reacts to the company. Can also be used to find out a review of a product.
<br><br>
There are two columns namely text and target in this dataset, that is : 
Text is the content of tweets that have been posted by users,
Target is the kind of sentiment that results from user tweets (0 = Negative sentimen, 1 = Positive sentimen)
<br><br>
In this program I want to do classification to know if there is a new tweet we can find out whether the tweet has positive or negative sentiments with several method. I use :
- Logistic Regression
- Naive Bayes
- K-Nearest Neighbor
- Random Forest Classifier
<br>Then I use CountVectorizer and TF-IDF to evaluate how important a word is to a document in a collection or corpus.<br>
Outline from this program is :
- Data preparation : to load dataset
- Data exploration : get to know with data 
- Data processing : to make raw data into quality data. <br>
  In Data processing I do : <br>
  1.  Stop words removal <br>
  2.  Tokenization <br>
  3.  Lematization <br>
- Data visualization : to visualize data
- Modelling :
  In Modelling I do : <br>
  - Create data sampling <br>
  - Train test splut <br>
  - Bag of word Count Vectorizer <br>
  - Finding TF-IDF <br>
