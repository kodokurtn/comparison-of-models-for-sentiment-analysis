# comparison-of-models-for-sentiment-analysis
#Сравнение моделей для сентиментного анализа текста 
в ноутбуке comprasion.ipynb содержится код, в котором сравниваются между собой 3 модели для сентиментного анализа текста

1.	blanchefort/rubert-base-cased-sentiment, которая основана на модели DeepPavlov/rubert-base-cased-conversational, и обучена на таких датасетах как: RuTweetCorp, RuReviews, RuSentiment и отзывах о медучреждениях;
2.	blanchefort/rubert-base-cased-sentiment-rurewiews, которая как и первая модель основана на DeepPavlov/rubert-base-cased-conversational, обучалась только на датасете RuReviews;
3.	cointegrated/rubert-tiny-sentiment-balanced, которая основана на модели cointegrated/ rubert-tiny, и дообучена на датасете SentiRuEval2016, для сентиментного анализа коротких текстов на русском языке.

Подробнее про сравнение и выбор модели можно почитать в этой статье: 
