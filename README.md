# Practical_Machine_Learning
Final Project Summary:
This project aims to foresee the way by which they did the exercise. The feature "classe" in the training dataset identifies the same. I have used Random Forest classifier to classify the exercise activities into 5 classes –A,B,C,D,E.
I have used training and testing datasets from the source:  
http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har. 
I have followed following steps:
1.	Loading the necessary R packages.
2.	Downloading the training dataset from
https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv
3.	Downloading the testing dataset from
https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv
4.	Data cleaning and dimensionality reduction. I removed the first 7 features as  1)X, 2)user_name, 3)raw_timestamp_part_1, 4)raw_timestamp_part_2, 5)cvtd_timestamp, 6)new_window, 7) num_window
5.	I have partitioned training dataset into 80% Training and 20% Validation Data set.
6.	I have used Random Forest classifier with 5-Fold cross validation to create my model.
7.	I have used the trained model to predict the classes of validation data set and produced the confusion matrix for the validation data set.
8.	Finally I used the same model to predict the classes of given testing (Quiz) dataset.
