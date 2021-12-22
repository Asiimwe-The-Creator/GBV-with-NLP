# GBV-with-NLP
Using Natural Language Processing to identify Gender Based Violence targeted tweets.
This is an imbalanced classification problem with five classes, the training and test set were obtained through a Stratified shuffle split using sklearn's StratifiedShuffleSplit. 
Pre-processing and feature engineering was done with Spacy for example for stop words removal, part-of-speech-tags analysis, lemmatization. Further pre-processing performed and explored includes new-tab removal, html-tag removal, removal of links, accented characters, lower casing, reducing incorrect character repeatition, special characters, expanding contractions and sentiment analysis with TextBlob.
Best model performance was obtained with unigrams and no stop-words at a 99.89% weighted average of F1-score using the Random Forest Classifier.
