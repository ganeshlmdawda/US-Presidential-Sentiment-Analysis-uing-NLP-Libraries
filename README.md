# Sentiment Analysis with NLTK and TextBlob

## Overview
This project aims to perform sentiment analysis on a dataset obtained from Kaggle using Natural Language Processing (NLP) libraries such as NLTK and TextBlob. The primary objective is to predict sentiment by leveraging polarity and subjectivity metrics provided by these libraries.

## Dependencies
- Python
- NLTK
- TextBlob
- Pandas
- Matplotlib (optional for visualization)

## Dataset
The dataset used in this project is obtained from Kaggle. It consists of Tweets collected, using the Twitter API statuses_lookup and snsscrape for keywords.

## Files
The dataset files are not included in this repository due to their large size. However, you can obtain the dataset from Kaggle and mount it into the project directory. Ensure the dataset is in CSV format and named appropriately.
- `sentiment_analysis.py`: The main script for sentiment analysis.
- `hashtag_joebiden.csv`: Consists of tweets with keywords #Biden and #JoeBiden.
- `hashtag_donaldtrump.csv`: Consists of tweets with keywords #Trump and #DonaldTrump.
  

## Approach
1. Load the dataset using Pandas.
2. Preprocess the text data (e.g., remove punctuation, stopwords, etc.).
3. Utilize NLTK for tokenization and TextBlob for sentiment analysis.
4. Calculate polarity and subjectivity metrics for each text.
5. Predict sentiment based on polarity scores (e.g., positive if polarity > 0, negative if polarity < 0, neutral otherwise).


## Results
The results of sentiment analysis, including polarity and subjectivity metrics, will be displayed or saved based on the implementation.
