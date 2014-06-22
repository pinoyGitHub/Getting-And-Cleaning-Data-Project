
### Getting and Cleaning Data Course Project

## Project Codebook:

##  Raw Data Set:

The project is based on Human Activity Recognition Using Smartphones, Complete descriptions can be access at : [Human Activity Recognition Using Smartphones ](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones ).

The  data can be downloaded  [here](Human Activity Recognition Using Smartphones ) 

## Cleaning the data set:

Training and Test sets were combined to create single data set (x_train.txt and y_train.txt store in X ). Using features.txt, regular expression "(mean|std)\\(" was used to filter out the measurement of the mean and standard deviation for each measurement (66 out of 551 attributes are measurements). Read activity_labels.txt and applies descriptive activity names to name the activities in the data set. In addition, Appropriately labels the data set with descriptive name (the first two columns namely "activity" and "subject" where in the "activity" column contains the activity names(eg standing,walking,sitting and etc ) "subject" column contains integers that range from 1 to 30. 

Finally, The tidy data set is saved to "tidydt.txt" with the average of each measurement for each activity and each subject. 
