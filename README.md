Getting-And-Cleaning-Data-Project
=================================


Getting and Cleaning Data Course (GCD) Project.

This is a repository of script/parser program called run_analysis.R 

## How the Script Works:
  
    0.1  The script download the data set and unzip the data
  
    0.2 Read the subject files, label and features files
  
  1. Read the training and test sets and merge them to create one data set
  2. Get only the measurement on the mean and standard deviation for each measurement
  3. Uses descriptive activity names to name the activities in the data set
  4. Appropriately labels the data set with descriptive activity names.
  5. independent tidy set with the average of each variable for each activity and each subject.

Notes: Comments are included on the program.

Data Source: [[Human Activity Recognition using Smartphones](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip )]

## Running the script
Using R Studio, simply open the file run_analysis.R, select all the content and click Run.
