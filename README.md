# sentiment-analysis
Sentiment Analysis Code

This code implements a sentiment analysis algorithm that classifies text as positive, negative, or neutral. 
The algorithm is based on the use of a sentiment lexicon, which is a dictionary of words and phrases that are associated with positive and negative sentiment.

The analysis is done on amazon reviews.tsv file.
A dataframe of the dataset is created.
Every row in dataframe is given a sentiment score using the NLTKs SentimentIntensityAnalyzer.
![image](https://github.com/SubhanshuWalia/sentiment-analysis/assets/150337661/56993546-c452-4e9c-9855-656555b95653)

Its 3 models are created:
-Naive bayes
-SVM
-Logistic Regression
Based on the confusion matrices of these threee models the accuracy of the model is verified.

Logistic Regression:
![image](https://github.com/SubhanshuWalia/sentiment-analysis/assets/150337661/cff0e1c6-1e2d-48bf-b70f-62f29f90e429)

SVM:
![image](https://github.com/SubhanshuWalia/sentiment-analysis/assets/150337661/a03c7bb3-c0b2-4296-8636-b209c10f4840)

Naive Bayes:
![image](https://github.com/SubhanshuWalia/sentiment-analysis/assets/150337661/c241b7d6-21be-4d39-b153-96bc4c60167d)

The model accuracy remains 75%.
