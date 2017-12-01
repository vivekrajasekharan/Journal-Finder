# Journal-Finder
Machine learning model to find suitable journals to submit scientific articles to, from the 'title' and 'abstract'. 

Details: Model placed right journal in the top 3 of 105 journals ~77% of the time for test data. Probabilities are outputted to reveal confidence in predicted class. The classifier used here is LinearSVC. LancasterStemmer is used to tokenize words and TFIDF Vectorizer is used to find a numeric representation of the text.

App coming soon!
