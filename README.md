# Getting-and-Cleaning-Data-Course-Project
This repository is a submission for the Getting and Cleaning Data course project. It contains the instructions on how to run an analysis on the Human Activity recognition dataset.

Dataset
Human Activity Recognition Using Smartphones

Files
CodeBook.md a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data

run_analysis.R performs the data preparation and then followed by the 5 steps required as described in the course project’s definition:
1. Merges the training and the test sets to create one data set.
2. Extracts only the mean and standard deviation variables for each measurement (specifically only those variables including mean() or std() in the description).
3. Uses descriptive activity names to name the activities in the data set.
4. Reuses the original variable name to appropriately label the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
FinalData.csv is the exported final data after going through all the sequences described above.
