# Сравнение моделей для сентиментного анализа текста 
в ноутбуке comprasion.ipynb содержится код, в котором сравниваются между собой 3 модели для сентиментного анализа текста

1.	blanchefort/rubert-base-cased-sentiment, которая основана на модели DeepPavlov/rubert-base-cased-conversational, и обучена на таких датасетах как: RuTweetCorp, RuReviews, RuSentiment и отзывах о медучреждениях;
2.	blanchefort/rubert-base-cased-sentiment-rurewiews, которая как и первая модель основана на DeepPavlov/rubert-base-cased-conversational, обучалась только на датасете RuReviews;
3.	cointegrated/rubert-tiny-sentiment-balanced, которая основана на модели cointegrated/ rubert-tiny, и дообучена на датасете SentiRuEval2016, для сентиментного анализа коротких текстов на русском языке.

Подробнее про сравнение и выбор модели можно почитать в этой статье: https://newtechaudit.ru/roboty-empaty-mif-ili-realnost/

# Comparing models for sentiment analysis of text 
The notebook comprasion.ipynb contains code that compares 3 models for sentiment analysis of text

1. blanchefort/rubert-base-cased-sentiment, which is based on the DeepPavlov/rubert-base-cased-conversational model, and trained on datasets such as: RuTweetCorp, RuReviews, RuSentiment and reviews about medical institutions;
2. blanchefort/rubert-base-cased-sentiment-rurewiews, which like the first model is based on DeepPavlov/rubert-base-cased-conversational, trained only on the RuReviews dataset;
3. cointegrated/rubert-tiny-sentiment-balanced, which is based on the cointegrated/rubert-tiny model, and was further trained on the SentiRuEval2016 dataset, for sentiment analysis of short texts in Russian.

You can read more about the comparison and choice of the model in this article: https://newtechaudit.ru/roboty-empaty-mif-ili-realnost/
