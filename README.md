# nlp_news_category

objectives: the objective of this repository is to create a nlp model for when you give the model the headline of the news and a short description it will return the genre of the news.

algorithms used:

1- [LogisticRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)

2- [MultinomialNB](sklearn.naive_bayes.MultinomialNB)

experiments:


at the beginning of the classification results process it was noted that the difference between the two algorithms was small but that the LogisticRegression would be the algorithm that would bring better results,
another thing that can be noticed was that the text without stemming brings better results than the text with stemming applied,
and also that tf-idf was better than CountVectorize.

results: the final accuracy of LogisticRegression model is 0.6018042776914805


[dataset used in this repository](https://www.kaggle.com/rmisra/news-category-dataset)


[raw_data from girhub that i used in the nootebook](https://raw.githubusercontent.com/dbstern/kaggle-news-category/master/input/News_Category_Dataset_v2.json)

obs: the raw data from github is the same of the kaggle dataset


