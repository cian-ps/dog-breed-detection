# Dog Breed Detection Project

## Problem Definition
Create a classifier capable of determining a dog's breed from a photo using Tensorflow.

## Data
Data comes from Kaggle's Dog Breed Identification competition.
You are provided with a training set and a test set of images of dogs. Each image has a filename that is its unique id. The dataset comprises 120 breeds of dogs. The goal of the competition is to create a classifier capable of determining a dog's breed from a photo.


* train.zip - the training set, you are provided the breed for these dogs
* test.zip - the test set, you must predict the probability of each breed for each image
* sample_submission.csv - a sample submission file in the correct format
* labels.csv - the breeds for the images in the train set


## Evaluation
Submissions are evaluated on **Multi Class Log Loss** between the predicted probability and the observed target.
