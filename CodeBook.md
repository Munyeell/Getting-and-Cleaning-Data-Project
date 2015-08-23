##CodeBook

This code book that describes the variables, the data and any transformations or work that you performed to clean up the data.

#DATA SET Description

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
