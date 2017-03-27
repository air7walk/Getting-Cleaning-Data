#Final Project:  Getting & Cleaning Data

##Creating an R Script (run_analysis.R) to do the following:
1.  Merges the training and the test sets to create one data set.
2.  Extracts only the measurements on the mean and standard deviation for each measurement.
3.  Uses descriptive activity names to name the activities in the data set
4.  Appropriately labels the data set with descriptive activity names.
5.  Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

#Important Notes:

1.  Download source data (UCI HAR dataset), and put run_analysis.R in the parent folder.  Use this as your working directory.
2.  Running "run_analysis.R" will generate the tiny_data.txt file in your working directory.
3.  This script will create the txt file with write.table() using row.name=FALSE.
