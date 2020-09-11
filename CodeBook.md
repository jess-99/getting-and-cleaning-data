This R script shows data preparation to the data set that has been downloaded followed by 5 steps that the assignment required

## First thing
download the data set 

## second thing
assigning the data to variables

    features <- features.txt : 561 rows, 2 columns
    The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ.
    activities <- activity_labels.txt : 6 rows, 2 columns
    List of activities performed when the corresponding measurements were taken and its codes (labels)
    subject_test <- test/subject_test.txt : 2947 rows, 1 column
    contains test data of 9/30 volunteer test subjects being observed
    x_test <- test/X_test.txt : 2947 rows, 561 columns
    contains recorded features test data
    y_test <- test/y_test.txt : 2947 rows, 1 columns
    contains test data of activities’code labels
    subject_train <- test/subject_train.txt : 7352 rows, 1 column
    contains train data of 21/30 volunteer subjects being observed
    x_train <- test/X_train.txt : 7352 rows, 561 columns
    contains recorded features train data
    y_train <- test/y_train.txt : 7352 rows, 1 columns
    contains train data of activities’code labels

## third thing
applying the 5 steps that required
   
    1-Merges the training and the test sets to create one data set.
    2-Extracts only the measurements on the mean and standard deviation for each measurement.
    3-Uses descriptive activity names to name the activities in the data set
    4-Appropriately labels the data set with descriptive variable names.
    5-From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.