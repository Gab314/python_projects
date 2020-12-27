# NLP for Sentimental Analysis
## Data Taken from Covid-19 Tweets

### Links:
[Kaggle](https://www.kaggle.com/datatattle/covid-19-nlp-text-classification)


##Data Overview:
32,567 Entries

![Sentiment_count](assets/sentiment_count.png)

> Columns:
>>+ UserName
>>+ ScreenName
>>+ Location
>>+ TweetAt
>>+ OriginalTweet
>>+ Sentiment

## Models:

+ Bag of Words, tested with a few **Scikit-learn** classifiers, and **NLKT** for data pre-processing.
+ LSTM, Simple Model with the words as input using **Keras** library.


## Model Overview:

`SGDClassifier` has produced our best Bag-of-words model with a 52% Accuracy.


![TextExplainer](assets/lime_text.png)


`LSTM` Simple Model with 68% Accuracy. 

![LSTM1_Summary](assets/lstm1_summary.png)
![LSTM1_AccLoss](assets/lstm1_acc_loss.png)