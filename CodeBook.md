##CodeBook

This code book that describes the variables, the data and any transformations or work that you performed to clean up the data.

#Description of the Data

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ.
These time domain signals (prefix ‘t’ to denote time) were captured at a constant rate of 50 Hz.and the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) – both using a low pass Butterworth filter.

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag).

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals).

These signals were used to estimate variables of the feature vector for each pattern:
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

* tbodyacc-xyz

* tgravityacc-xyz

* tbodyaccjerk-xyz

* tbodygyro-xyz

* tbodygyrojerk-xyz

* tbodyaccmag

* tgravityaccmag

* tbodyaccjerkmag

* tbodygyromag

* tbodygyrojerkmag

* fbodyacc-xyz

* fbodyaccjerk-xyz

* fbodygyro-xyz

* fbodyaccmag

* fbodyaccjerkmag

* fbodygyromag

* fbodygyrojerkmag

The set of variables that were estimated from these signals are:

* mean: Mean value

* std: Standard deviation

#Files in folder ‘UCI HAR Dataset’ that will be used are:
1. SUBJECT FILES 
  * test/subject_test.txt
  * train/subject_train.txt
2.  ACTIVITY FILES
  * test/X_test.txt
  * train/X_train.txt
3.  DATA FILES
  * test/y_test.txt
  * train/y_train.txt
4.  Features.txt - Names of column variables in the dataTable
5.  activity_labels.txt - Links the class labels with their activity name.


#Details Transformation

There are 5 session:

1. Merges the training and the test sets to create on data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set.
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
