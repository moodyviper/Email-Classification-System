# Spam Comment Detector

This repository is based on the flask framework web application, with the help of Machine Learning, the application is capable to detect that the comment is spam or not.The goal of our project was to create a machine learning model that can produce output for anyone. Our project has an integrated API structure that recieves user's queries and responds to them with the output of our spam comment classifier model when fed with the query input parameter.

## Flask

A microframework based on Werkzeug. It's extensively documented
and follows best practice patterns.

## Model

#### CountVectorizer

Convert a collection of text documents to a matrix of token counts.This implementation produces a sparse representation of the counts using
scipy.sparse.coo_matrix.

If you do not provide an a-priori dictionary and you do not use an analyzer
that does some kind of feature selection then the number of features will
be equal to the vocabulary size found by analyzing the data.

#### Naive Bayes classifier for multinomial models

The multinomial Naive Bayes classifier is suitable for classification with
discrete features (e.g., word counts for text classification). The
multinomial distribution normally requires integer feature counts. However,
in practice, fractional counts such as tf-idf may also work.

### GUI
### Inital Screen
<img title="" src="/guiimages/mainscreen.png" alt="">
<br>

### Spam Screen

<img title="" src="/guiimages/spamscreen.png" alt="">
<br>

### Ham Screen

<img title="" src="/guiimages/hamscreen.png" alt="">

