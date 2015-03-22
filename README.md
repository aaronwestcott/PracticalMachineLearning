# PracticalMachineLearning
Coursera Practical Machine Learning Project
This is the practical machine learning project for the coursear data science track.

The data was examined for nulls, NAs and other invalid values and cleaned up appropriately.  I eliminated the columns that had more than 1000 NAs after converting anything that I could find to an NA.  This cut down on the number of columns to consider as predictors.  

I split the training set into train and test and then trained a random forest on the training set and eamined the error on the testing set.  I did this by getting the percentage of crrect predicitons out of the total.  The error was in the order of ~99% correct.

