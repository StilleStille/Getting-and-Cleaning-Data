Getting-and-Cleaning-Data
=========================


This repo contains project code for Getting and Cleaning Data course given by John Hopkins university on Coursera.


Here are the data for the project: 

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

 
Download the data source and put into a folder on your local drive.


You'll have a UCI HAR Dataset folder.
Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.  setwd ("~/UCI HAR Dataset") 


R script "run_analysis.R" does the following:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Run source("run_analysis.R"), then it will generate a new file  data_set_with_the_averages.txt in your working directory.


