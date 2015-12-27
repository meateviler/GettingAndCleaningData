Getting And Cleaning Data project

Source data from 
A full description is available at the site where the data was obtained: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Here are the data for the project: 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 


Step 1. Merges the training and the test sets to create one data set.
in this step we need use those file
train/X_train.txt
train/Y_train.txt
train/subject_train.txt
test/X_test.txt
test/Y_test.txt
test/subject_test.txt
and merge them

Step 2. Extracts only the measurements on the mean and standard deviation for each measurement. 
in this step we need the features.txt
get only columns with mean() or std() in their names

Step 3. Uses descriptive activity names to name the activities in the data set
in this step we need activity_labels.txt
update values with correct activity names

Step 4. Appropriately labels the data set with descriptive variable names. 
in this step we will bind all the data in a single data set

Step 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
in this step we will create our tidy_data.txt
