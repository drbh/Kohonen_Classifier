# Kohonen_Classifier
Script for SPSS class assignment to classify Kohonen Net Results

The library dplyr is needed

No need for a file path, the function file.choose() allows a user to select the .csv from 


Input for getting classifications
- Must be a csv file from SPSS modeler
- Must have columns named 'X.KXY.Kohonen' and 'Income.Level' 
- 'Income.Level' must have " >50K."

Input for classifying
- Must be a csv file from SPSS modeler
- Must have columns named 'X.KXY.Kohonen'


The function 
getAccuracy() can be used to make a confusion matrix and get overall accuracy. In order to use this function labeled, must have an 'Income.Level' column 

[pretty much just to see how accurate the model was on your test data]

