# Getting-and-Cleaning-Data-Course-Project
##Review criteria
- The submitted data set is tidy. 

- The Github repo contains the required scripts.

- GitHub contains a code book that modifies and updates the available codebooks with the data to indicate all the variables and summaries calculated, along with units, and any other relevant information.

- The README that explains the analysis files is clear and understandable.

- The work submitted for this project is the work of the student who submitted it.


You should create one R script called run_analysis.R that does the following. 

Merges the training and the test sets to create one data set.

Extracts only the measurements on the mean and standard deviation for each measurement. 

Uses descriptive activity names to name the activities in the data set

Appropriately labels the data set with descriptive variable names. 

From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


##HERE IS EXPLANTION OF THE PROJECT
File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work):

Merging the training and the test sets to create one data set.
1. Read files
1.1 Reading trainings tables
1.2 Reading testing tables
1.3 Reading feature vector
1.4 Reading activity labels
2 Assigning column names
3 Merging all data in one set

Extracting only the measurements on the mean and standard deviation for each measurement
1 Reading column names
2 Create vector for defining ID, mean and standard deviation
3 Making nessesary subset from setAllInOne
Using descriptive activity names to name the activities in the data set
Appropriately labeling the data set with descriptive variable names
Creating a second, independent tidy data set with the average of each variable for each activity and each subject
1 Making second tidy data set
2 Writing second tidy data set in txt file
