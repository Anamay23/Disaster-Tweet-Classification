# Disaster-Tweet-Classification

This project looks to tackle the problem of fake news by looking to correctly classify tweets based on whether they contain fake news or not. With the number of tweets rising everyday and seeing the influence they can have on people, this project is important and has real time applications. We have used a dataset of 10,000 tweets and are going to classify which ones are talking about real disasters and which ones are not.

Text data is pre-processed to convert it into a consistent format. Text is also cleaned, tokenized and converted into a matrix. Data cleaning mainly involved removing noise, Tokenization, stop word removal, removing emojis, html tags, punctuations, and URL, Stemming and Lemmatization. Broad steps followed are- EDA, Data Cleaning, Creating cloud words, CountVectorizer and TFIDF Vectorizer and GloVe.

Results: A look at the history of the performance of the sequential GloVe model we created using a sigmoid activation function, adam optimizer and 10 epochs tells us that we achieved a final accuracy of 81% on the 10th epoch.


