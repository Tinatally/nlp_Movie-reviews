# nlp_Movie-reviews
About the Project: The Film Junky Union, a new edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. The goal is to train a model to automatically detect negative reviews. You'll be using a dataset of IMBD movie reviews with polarity labelling to build a model for classifying positive and negative reviews. It will need to reach an F1 score of at least 0.85.

After exploring and traing the data using different models, the following results were generated:

||model|F1 Score Train|F1 score Test|
|---|---|---|---|
|1|Logistic Regression TF-IDF|0.94|0.88|
|2|Logistic Regression Spacy|0.93|0.87|
|3|LightGBM |0.91|0.85|
|4|BERT |0.87|0.86|
