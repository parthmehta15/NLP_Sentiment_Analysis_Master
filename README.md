# NLP_sentiment

This repo contains different methods for Sentiment Analysis.

*BERT_Finetuning_sentiment.ipynb* -> Contains method to finetune Bert model from Transforers (🤗) library. Along with monitoring metrics in WanDB.  The data is Rotten Tomatoes movei review dataset.
(https://www.kaggle.com/competitions/sentiment-analysis-on-movie-reviews/data). The reviews can be classsified into five classes.
The sentiment labels are:
0 - negative
1 - somewhat negative
2 - neutral
3 - somewhat positive
4 - positive


*Flair_Sentiment.ipynb* -> Contains method for sentiment analysis using Flair library.


*Sentiment_Transformers_FinBert.ipynb* -> Contains method for sentiment analysis on financial data using pretrained Finance BERT (FinBert) model.


*LongText_Sentiment_Transformers.ipynb* -> Contains method for sentiment analysis on long text using window method on financial data using pretrained Finance BERT (FinBert) model.
