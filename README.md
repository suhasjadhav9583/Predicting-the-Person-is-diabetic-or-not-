# Predicting-the-Person-is-diabetic-or-not-
This is the system used with technoloy like python and machine learning especially using support vector machine to predict the person is diabetic or not


####work flow of the project is::

1)collecting the data from various sources in CSV format
2)data cleaning
3)Data preprocessing (standardizing the data in the same range many target columns does not have value in the same range so with help of transform we can easily standardised the data)
4)Train Test Split(and find accuracy score)
5)Use a Support vector Machine Classifier to classify the result in hyperplanes and feed the data to the system
6)trained the data to SVM classifier and newly added data get classified with the help of hyperplanes 
7)predict the output of the data


## algoritm used:--SVM(support vector machine)

##library Used:
import numpy as np
import pandas as pd
from sklearn.preprocessing import StandardScaler# used the data to standardise in a range
from sklearn.model_selection import train_test_split
from sklearn import svm  
from sklearn.metrics import accuracy_score
