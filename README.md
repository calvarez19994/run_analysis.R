# run_analysis.R

For the getting and cleaning data assignment you should create one R script called run_analysis.R that does the following.

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Download the data source and put into your working directory. You'll have a UCI HAR Dataset folder in your working folder. Put run_analysis.R in your wirking folder, then set it as your working directory using setwd() function in RStudio. Run source("run_analysis.R"), then it will generate a new file tidy_data.txt in your working directory.
