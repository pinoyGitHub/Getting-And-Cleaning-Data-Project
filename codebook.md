
Getting and Cleaning Data Course Project

Project Codebook:

Raw Data Set:

The project is based on Human Activity Recognition Using Smartphones: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
and data can be downloaded to https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

Cleaning the data set:


Training and Test sets were combined to create single data set (x_train.txt and y_train.txt). Using features.txt, regular expression "(mean|std)\\(" was used to filter out the measurement of the mean and standard deviation for each measurement (66 out of 551 attributes are measurements)
Read activity_labels.txt and applies descriptive activity names to name the activities in the data set: ( data sets: walking, sitting, standing and etc) appropriately labels the data set with descriptive names. 

Finally, The tidy data set is saved to "tidydt.txt" with the average of each measurement for each activity and each subject (180 X 68 data frame). 
