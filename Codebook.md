+## Getting and Cleaning Data Project

+### Description
+Additional information about the variables, data and transformations used in the course project for the Johns Hopkins Getting and Cleaning Data course.
+
+### Source Data
+A full description of the data used in this project can be found at [The UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
+
+[The source data for this project can be found here.](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)
+
+### Part 1. Merge the training and the test sets to create one data set.
+After setting the source directory for the files, read into tables the data located in
+- features.txt
+- activity_labels.txt
+- subject_train.txt
+- x_train.txt
+- y_train.txt
+- subject_test.txt
+- x_test.txt
+- y_test.txt
+
+Assign column names and merge to create one data set.
+
+## Part 2. Extract only the measurements on the mean and standard deviation for each measurement. 
+Create a logical vector that contains TRUE values for the ID, mean and STDEV columns and FALSE values for the others.
+Subset this data with grep and gsub to keep only the necessary columns.
+
+## Part 3. Use descriptive activity names to name the activities in the data set
+Merge data subset with the activityType table to inlude the descriptive activity names
+
+## Part 4. Appropriately label the data set with descriptive activity names.
+
+
+## Part 5. Create a second, independent tidy data set with the average of each variable for each activity and each subject. 
+Per the project instructions, we need to produce only a data set with the average of each variable for each activity and subject