# nlp_news_category

objectives: the objective of this repository is to create a nlp bot for when you give the robot the headline of the news and a short description it will return the genre of the news so you can automate the process when you post the news in it genre 

algorithms used:

1- LogisticRegression,

2- MultinomialNB

experiments:


at the beginning of the classification results process it was noted that the difference between the two algorithms was small but that the LogisticRegression would be the algorithm that would bring better results,
another thing that can be noticed was that the text without stemming brings better results than the text with stemming applied,
and also that tf-idf was better than CountVectorize.

results: the final accuracy of LogisticRegression model is 0.6018042776914805

link of the data set used in this repository: https://www.kaggle.com/rmisra/news-category-dataset

link of the raw_data that is used in the nootebook: https://raw.githubusercontent.com/dbstern/kaggle-news-category/master/input/News_Category_Dataset_v2.json
