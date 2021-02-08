# Naive Bayes Classification

## Problem 1:
You are given a dataset of textual summary of medical queries classified into five different categories. You have to build your **own naïve Bayes classifier** to predict these categories for future queries i.e. without using builtin libraries in python. The task includes:
* Implement Learn(..) method that takes training and test data (in the form of word vectors) and learns its Naïve Bayes classifier. You have to do your own implementation of Naïve Bayes here.
* Some conditional probabilities may turn out to be zero in the training dataset. Modify your classifier such that it applies Laplacian smoothing while learning conditional probabilities to avoid such zero values.
* Implement Predict(…) that takes a learned classifier and test data and returns predicted values.
* Implement Evaluate(…) that takes actual and predicted labels and returns precision, recall, f-measure. The method will also display confusion matrix.

## Problem 2: 
You are given a Fashion-MNIST dataset comprising of 28x28 grayscale images of 60,000 fashion products from 10 categories, with 7,000 images per category. The training set has 60,000 images and the test set has 10,000 images. You have to build a scikit-learn based classifier for this dataset to classify each input image into one (out
of 10) categories. You are required to experiment with three to four different classifiers and report accuracy of each of them.
