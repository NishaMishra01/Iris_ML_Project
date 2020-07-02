# Iris_ML_Project
The aim of this project is to classify iris flowers among three species 
( setosa , versicolor , or virginica) from measurements of sepals and petals length and width.

The iris data set contains 3 classes.
This is a classification project,since the variable to predicted is categorical( setosa ,versicolor , or virginica ).
In This : Our data has 150 samples with 4 features each (sepal length (cm), sepal width (cm), petal length(cm) ,petal width (cm)).
The target array contains the species of each flowers that were measured.This array is composed of number from 0 to 2

* setosa (0)
* versicolor(1)
* virginica(2)


To test the model's performance, we show it new data for which we have labels. This is usually done by splitting the labelled data have collect into two parts.
One part of data is used to buid the machine learning model, and is called the training data or training set(which we will call x_train and y_train). 
The rest of data will be used to test how well model works; this is called test set (which is x_test, y_test).


scikit-learn has a function that shuffles and splits the data set: the train_test_split function.
now building the actual model with the use of Logistic Regression. To make the prediction for a new data point.
also use the score method to compute the test set accuracy.

