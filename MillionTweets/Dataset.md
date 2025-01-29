### Sentiment140 Dataset with 1.6 million tweets
- [Dataset Link][https://www.kaggle.com/datasets/kazanova/sentiment140/data]
- Contains 1,600,000 tweets extracted using the twitter api.
- Tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment.

#### Fields 
- **target** (Int) : the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
- **ids** (Int) : The id of the tweet (2087)
- **date** (String) : the date of the tweet (Sat May 16 23:58:44 UTC 2009)
- **flag** (String) : The query (lyx). If there is no query, then this value is NO_QUERY.
- **users** (String) : the user that tweetes (robotickilldozr)
- **text** (String) : the text of the tweet (Lyx is cool)

#### Dataset Information 
- There are no missing values.
- Fiels are not in the dataset, have to manually add them.
- 1600000 rows and 6 columns.

#### Notebook 1: Twitter_Sentiment_NLP_LR
- Out of 6 fields only 2 are used - target and text.
- Additionally new field is created - 'stemmed_text'.
