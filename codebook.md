Source of the original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The R script (run_analysis.R) performs the following to clean up the data:

1. Merges the training and the test sets to create one data set.

2. Reads features.txt and extracts only the measurements on the mean and standard deviation for each measurement.

3. Reads activity_labels.txt and applies descriptive activity names to name the activities in the data set:

walking

walkingupstairs

walkingdownstairs

sitting

standing

laying

4. Appropriately labels the data set with descriptive variable names as following:

tbodyacc-mean-x 

tbodyacc-mean-y 

tbodyacc-mean-z 

tbodyacc-std-x 

tbodyacc-std-y 

tbodyacc-std-z 

tgravityacc-mean-x  


5. It finally creates a second, independent tidy data set with the average of each variable for each activity and each subject. 