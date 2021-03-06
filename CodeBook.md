Code Book
=================

The variables in this data set are best understood in parts separated by dots.
The general format is:

**activityType.accelerometerMovementFeatureOrMeasure.statisticalValue.
axialDirection**

The one exception to this scheme is subjectID which identifies subjects 1 through 30.

## Activity Type:

Each subject engaged in 6 activities that were recorded by the cell phone accelerometer.

walking

walkingUpstairs

walkingDownstairs

standing

sitting

laying

## Accelerometer Movement Feature or Measure:

The features selected for this database come from the accelerometer and
gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain
signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz.
Then they were filtered using a median filter and a 3rd order low pass
Butterworth filter with a corner frequency of 20 Hz to remove noise.
Similarly, the acceleration signal was then separated into body and gravity
acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass
Butterworth filter with a corner frequency of 0.3 Hz.

Subsequently, the body linear acceleration and angular velocity were derived
in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also
the magnitude of these three-dimensional signals were calculated using the
Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag,
tBodyGyroJerkMag).

Finally a Fast Fourier Transform (FFT) was applied to some of these signals
producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag,
fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain
signals).

These signals were used to estimate variables of the feature vector for each
pattern:
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

tBodyAcc-XYZ

tGravityAcc-XYZ

tBodyAccJerk-XYZ

tBodyGyro-XYZ

tBodyGyroJerk-XYZ

tBodyAccMag

tGravityAccMag

tBodyAccJerkMag

tBodyGyroMag

tBodyGyroJerkMag

fBodyAcc-XYZ

fBodyAccJerk-XYZ

fBodyGyro-XYZ

fBodyAccMag

fBodyAccJerkMag

fBodyGyroMag

fBodyGyroJerkMag

**Additional vectors were obtained by averaging the signals in a signal window
sample. These are used on the angle() variable:**

gravityMean

tBodyAccMean

tBodyAccJerkMean

tBodyGyroMean

tBodyGyroJerkMean

**Angle variables denote the angle between the two vectors (V). Each vector is
separated by (BY).**

angleVtBodyAccMeanBYgravityMean

angleVtBodyAccJerkMeanBYgravityMean

angleVtBodyGyroMeanBYgravityMean

angleVtBodyGyroJerkMeanBYgravityMean

angleVxBYgravityMean

angleVyBYgravityMean

angleVzBYgravityMean

## Statistical Value

mean = Mean

std = Standard Deviation

## Axial Direction: If present in the accelerometer movement feature above

x

y

z

## Complete List of Variables

subjectID

walking.tBodyAcc.mean.x

walking.tBodyAcc.mean.y

walking.tBodyAcc.mean.z

walking.tBodyAcc.std.x

walking.tBodyAcc.std.y

walking.tBodyAcc.std.z

walking.tGravityAcc.mean.x

walking.tGravityAcc.mean.y

walking.tGravityAcc.mean.z

walking.tGravityAcc.std.x

walking.tGravityAcc.std.y

walking.tGravityAcc.std.z

walking.tBodyAccJerk.mean.x

walking.tBodyAccJerk.mean.y

walking.tBodyAccJerk.mean.z

walking.tBodyAccJerk.std.x

walking.tBodyAccJerk.std.y

walking.tBodyAccJerk.std.z

walking.tBodyGyro.mean.x

walking.tBodyGyro.mean.y

walking.tBodyGyro.mean.z

walking.tBodyGyro.std.x

walking.tBodyGyro.std.y

walking.tBodyGyro.std.z

walking.tBodyGyroJerk.mean.x

walking.tBodyGyroJerk.mean.y

walking.tBodyGyroJerk.mean.z

walking.tBodyGyroJerk.std.x

walking.tBodyGyroJerk.std.y

walking.tBodyGyroJerk.std.z

walking.tBodyAccMag.mean

walking.tBodyAccMag.std

walking.tGravityAccMag.mean

walking.tGravityAccMag.std

walking.tBodyAccJerkMag.mean

walking.tBodyAccJerkMag.std

walking.tBodyGyroMag.mean

walking.tBodyGyroMag.std

walking.tBodyGyroJerkMag.mean

walking.tBodyGyroJerkMag.std

walking.fBodyAcc.mean.x

walking.fBodyAcc.mean.y

walking.fBodyAcc.mean.z

walking.fBodyAcc.std.x

walking.fBodyAcc.std.y

walking.fBodyAcc.std.z

walking.fBodyAcc.meanFreq.x

walking.fBodyAcc.meanFreq.y

walking.fBodyAcc.meanFreq.z

walking.fBodyAccJerk.mean.x

walking.fBodyAccJerk.mean.y

walking.fBodyAccJerk.mean.z

walking.fBodyAccJerk.std.x

walking.fBodyAccJerk.std.y

walking.fBodyAccJerk.std.z

walking.fBodyAccJerk.meanFreq.x

walking.fBodyAccJerk.meanFreq.y

walking.fBodyAccJerk.meanFreq.z

walking.fBodyGyro.mean.x

walking.fBodyGyro.mean.y

walking.fBodyGyro.mean.z

walking.fBodyGyro.std.x

walking.fBodyGyro.std.y

walking.fBodyGyro.std.z

walking.fBodyGyro.meanFreq.x

walking.fBodyGyro.meanFreq.y

walking.fBodyGyro.meanFreq.z

walking.fBodyAccMag.mean

walking.fBodyAccMag.std

walking.fBodyAccMag.meanFreq

walking.fBodyBodyAccJerkMag.mean

walking.fBodyBodyAccJerkMag.std

walking.fBodyBodyAccJerkMag.meanFreq

walking.fBodyBodyGyroMag.mean

walking.fBodyBodyGyroMag.std

walking.fBodyBodyGyroMag.meanFreq

walking.fBodyBodyGyroJerkMag.mean

walking.fBodyBodyGyroJerkMag.std

walking.fBodyBodyGyroJerkMag.meanFreq

walking.angleVtBodyAccMeanBYgravityMean

walking.angleVtBodyAccJerkMeanBYgravityMean

walking.angleVtBodyGyroMeanBYgravityMean

walking.angleVtBodyGyroJerkMeanBYgravityMean

walking.angleVxBYgravityMean

walking.angleVyBYgravityMean

walking.angleVzBYgravityMean

walkingUpstairs.tBodyAcc.mean.x

walkingUpstairs.tBodyAcc.mean.y

walkingUpstairs.tBodyAcc.mean.z

walkingUpstairs.tBodyAcc.std.x

walkingUpstairs.tBodyAcc.std.y

walkingUpstairs.tBodyAcc.std.z

walkingUpstairs.tGravityAcc.mean.x

walkingUpstairs.tGravityAcc.mean.y

walkingUpstairs.tGravityAcc.mean.z

walkingUpstairs.tGravityAcc.std.x

walkingUpstairs.tGravityAcc.std.y

walkingUpstairs.tGravityAcc.std.z

walkingUpstairs.tBodyAccJerk.mean.x

walkingUpstairs.tBodyAccJerk.mean.y

walkingUpstairs.tBodyAccJerk.mean.z

walkingUpstairs.tBodyAccJerk.std.x

walkingUpstairs.tBodyAccJerk.std.y

walkingUpstairs.tBodyAccJerk.std.z

walkingUpstairs.tBodyGyro.mean.x

walkingUpstairs.tBodyGyro.mean.y

walkingUpstairs.tBodyGyro.mean.z

walkingUpstairs.tBodyGyro.std.x

walkingUpstairs.tBodyGyro.std.y

walkingUpstairs.tBodyGyro.std.z

walkingUpstairs.tBodyGyroJerk.mean.x

walkingUpstairs.tBodyGyroJerk.mean.y

walkingUpstairs.tBodyGyroJerk.mean.z

walkingUpstairs.tBodyGyroJerk.std.x

walkingUpstairs.tBodyGyroJerk.std.y

walkingUpstairs.tBodyGyroJerk.std.z

walkingUpstairs.tBodyAccMag.mean

walkingUpstairs.tBodyAccMag.std

walkingUpstairs.tGravityAccMag.mean

walkingUpstairs.tGravityAccMag.std

walkingUpstairs.tBodyAccJerkMag.mean

walkingUpstairs.tBodyAccJerkMag.std

walkingUpstairs.tBodyGyroMag.mean

walkingUpstairs.tBodyGyroMag.std

walkingUpstairs.tBodyGyroJerkMag.mean

walkingUpstairs.tBodyGyroJerkMag.std

walkingUpstairs.fBodyAcc.mean.x

walkingUpstairs.fBodyAcc.mean.y

walkingUpstairs.fBodyAcc.mean.z

walkingUpstairs.fBodyAcc.std.x

walkingUpstairs.fBodyAcc.std.y

walkingUpstairs.fBodyAcc.std.z

walkingUpstairs.fBodyAcc.meanFreq.x

walkingUpstairs.fBodyAcc.meanFreq.y

walkingUpstairs.fBodyAcc.meanFreq.z

walkingUpstairs.fBodyAccJerk.mean.x

walkingUpstairs.fBodyAccJerk.mean.y

walkingUpstairs.fBodyAccJerk.mean.z

walkingUpstairs.fBodyAccJerk.std.x

walkingUpstairs.fBodyAccJerk.std.y

walkingUpstairs.fBodyAccJerk.std.z

walkingUpstairs.fBodyAccJerk.meanFreq.x

walkingUpstairs.fBodyAccJerk.meanFreq.y

walkingUpstairs.fBodyAccJerk.meanFreq.z

walkingUpstairs.fBodyGyro.mean.x

walkingUpstairs.fBodyGyro.mean.y

walkingUpstairs.fBodyGyro.mean.z

walkingUpstairs.fBodyGyro.std.x

walkingUpstairs.fBodyGyro.std.y

walkingUpstairs.fBodyGyro.std.z

walkingUpstairs.fBodyGyro.meanFreq.x

walkingUpstairs.fBodyGyro.meanFreq.y

walkingUpstairs.fBodyGyro.meanFreq.z

walkingUpstairs.fBodyAccMag.mean

walkingUpstairs.fBodyAccMag.std

walkingUpstairs.fBodyAccMag.meanFreq

walkingUpstairs.fBodyBodyAccJerkMag.mean

walkingUpstairs.fBodyBodyAccJerkMag.std

walkingUpstairs.fBodyBodyAccJerkMag.meanFreq

walkingUpstairs.fBodyBodyGyroMag.mean

walkingUpstairs.fBodyBodyGyroMag.std

walkingUpstairs.fBodyBodyGyroMag.meanFreq

walkingUpstairs.fBodyBodyGyroJerkMag.mean

walkingUpstairs.fBodyBodyGyroJerkMag.std

walkingUpstairs.fBodyBodyGyroJerkMag.meanFreq

walkingUpstairs.angleVtBodyAccMeanBYgravityMean

walkingUpstairs.angleVtBodyAccJerkMeanBYgravityMean

walkingUpstairs.angleVtBodyGyroMeanBYgravityMean

walkingUpstairs.angleVtBodyGyroJerkMeanBYgravityMean

walkingUpstairs.angleVxBYgravityMean

walkingUpstairs.angleVyBYgravityMean

walkingUpstairs.angleVzBYgravityMean

walkingDownstairs.tBodyAcc.mean.x

walkingDownstairs.tBodyAcc.mean.y

walkingDownstairs.tBodyAcc.mean.z

walkingDownstairs.tBodyAcc.std.x

walkingDownstairs.tBodyAcc.std.y

walkingDownstairs.tBodyAcc.std.z

walkingDownstairs.tGravityAcc.mean.x

walkingDownstairs.tGravityAcc.mean.y

walkingDownstairs.tGravityAcc.mean.z

walkingDownstairs.tGravityAcc.std.x

walkingDownstairs.tGravityAcc.std.y

walkingDownstairs.tGravityAcc.std.z

walkingDownstairs.tBodyAccJerk.mean.x

walkingDownstairs.tBodyAccJerk.mean.y

walkingDownstairs.tBodyAccJerk.mean.z

walkingDownstairs.tBodyAccJerk.std.x

walkingDownstairs.tBodyAccJerk.std.y

walkingDownstairs.tBodyAccJerk.std.z

walkingDownstairs.tBodyGyro.mean.x

walkingDownstairs.tBodyGyro.mean.y

walkingDownstairs.tBodyGyro.mean.z

walkingDownstairs.tBodyGyro.std.x

walkingDownstairs.tBodyGyro.std.y

walkingDownstairs.tBodyGyro.std.z

walkingDownstairs.tBodyGyroJerk.mean.x

walkingDownstairs.tBodyGyroJerk.mean.y

walkingDownstairs.tBodyGyroJerk.mean.z

walkingDownstairs.tBodyGyroJerk.std.x

walkingDownstairs.tBodyGyroJerk.std.y

walkingDownstairs.tBodyGyroJerk.std.z

walkingDownstairs.tBodyAccMag.mean

walkingDownstairs.tBodyAccMag.std

walkingDownstairs.tGravityAccMag.mean

walkingDownstairs.tGravityAccMag.std

walkingDownstairs.tBodyAccJerkMag.mean

walkingDownstairs.tBodyAccJerkMag.std

walkingDownstairs.tBodyGyroMag.mean

walkingDownstairs.tBodyGyroMag.std

walkingDownstairs.tBodyGyroJerkMag.mean

walkingDownstairs.tBodyGyroJerkMag.std

walkingDownstairs.fBodyAcc.mean.x

walkingDownstairs.fBodyAcc.mean.y

walkingDownstairs.fBodyAcc.mean.z

walkingDownstairs.fBodyAcc.std.x

walkingDownstairs.fBodyAcc.std.y

walkingDownstairs.fBodyAcc.std.z

walkingDownstairs.fBodyAcc.meanFreq.x

walkingDownstairs.fBodyAcc.meanFreq.y

walkingDownstairs.fBodyAcc.meanFreq.z

walkingDownstairs.fBodyAccJerk.mean.x

walkingDownstairs.fBodyAccJerk.mean.y

walkingDownstairs.fBodyAccJerk.mean.z

walkingDownstairs.fBodyAccJerk.std.x

walkingDownstairs.fBodyAccJerk.std.y

walkingDownstairs.fBodyAccJerk.std.z

walkingDownstairs.fBodyAccJerk.meanFreq.x

walkingDownstairs.fBodyAccJerk.meanFreq.y

walkingDownstairs.fBodyAccJerk.meanFreq.z

walkingDownstairs.fBodyGyro.mean.x

walkingDownstairs.fBodyGyro.mean.y

walkingDownstairs.fBodyGyro.mean.z

walkingDownstairs.fBodyGyro.std.x

walkingDownstairs.fBodyGyro.std.y

walkingDownstairs.fBodyGyro.std.z

walkingDownstairs.fBodyGyro.meanFreq.x

walkingDownstairs.fBodyGyro.meanFreq.y

walkingDownstairs.fBodyGyro.meanFreq.z

walkingDownstairs.fBodyAccMag.mean

walkingDownstairs.fBodyAccMag.std

walkingDownstairs.fBodyAccMag.meanFreq

walkingDownstairs.fBodyBodyAccJerkMag.mean

walkingDownstairs.fBodyBodyAccJerkMag.std

walkingDownstairs.fBodyBodyAccJerkMag.meanFreq

walkingDownstairs.fBodyBodyGyroMag.mean

walkingDownstairs.fBodyBodyGyroMag.std

walkingDownstairs.fBodyBodyGyroMag.meanFreq

walkingDownstairs.fBodyBodyGyroJerkMag.mean

walkingDownstairs.fBodyBodyGyroJerkMag.std

walkingDownstairs.fBodyBodyGyroJerkMag.meanFreq

walkingDownstairs.angleVtBodyAccMeanBYgravityMean

walkingDownstairs.angleVtBodyAccJerkMeanBYgravityMean

walkingDownstairs.angleVtBodyGyroMeanBYgravityMean

walkingDownstairs.angleVtBodyGyroJerkMeanBYgravityMean

walkingDownstairs.angleVxBYgravityMean

walkingDownstairs.angleVyBYgravityMean

walkingDownstairs.angleVzBYgravityMean

sitting.tBodyAcc.mean.x

sitting.tBodyAcc.mean.y

sitting.tBodyAcc.mean.z

sitting.tBodyAcc.std.x

sitting.tBodyAcc.std.y

sitting.tBodyAcc.std.z

sitting.tGravityAcc.mean.x

sitting.tGravityAcc.mean.y

sitting.tGravityAcc.mean.z

sitting.tGravityAcc.std.x

sitting.tGravityAcc.std.y

sitting.tGravityAcc.std.z

sitting.tBodyAccJerk.mean.x

sitting.tBodyAccJerk.mean.y

sitting.tBodyAccJerk.mean.z

sitting.tBodyAccJerk.std.x

sitting.tBodyAccJerk.std.y

sitting.tBodyAccJerk.std.z

sitting.tBodyGyro.mean.x

sitting.tBodyGyro.mean.y

sitting.tBodyGyro.mean.z

sitting.tBodyGyro.std.x

sitting.tBodyGyro.std.y

sitting.tBodyGyro.std.z

sitting.tBodyGyroJerk.mean.x

sitting.tBodyGyroJerk.mean.y

sitting.tBodyGyroJerk.mean.z

sitting.tBodyGyroJerk.std.x

sitting.tBodyGyroJerk.std.y

sitting.tBodyGyroJerk.std.z

sitting.tBodyAccMag.mean

sitting.tBodyAccMag.std

sitting.tGravityAccMag.mean

sitting.tGravityAccMag.std

sitting.tBodyAccJerkMag.mean

sitting.tBodyAccJerkMag.std

sitting.tBodyGyroMag.mean

sitting.tBodyGyroMag.std

sitting.tBodyGyroJerkMag.mean

sitting.tBodyGyroJerkMag.std

sitting.fBodyAcc.mean.x

sitting.fBodyAcc.mean.y

sitting.fBodyAcc.mean.z

sitting.fBodyAcc.std.x

sitting.fBodyAcc.std.y

sitting.fBodyAcc.std.z

sitting.fBodyAcc.meanFreq.x

sitting.fBodyAcc.meanFreq.y

sitting.fBodyAcc.meanFreq.z

sitting.fBodyAccJerk.mean.x

sitting.fBodyAccJerk.mean.y

sitting.fBodyAccJerk.mean.z

sitting.fBodyAccJerk.std.x

sitting.fBodyAccJerk.std.y

sitting.fBodyAccJerk.std.z

sitting.fBodyAccJerk.meanFreq.x

sitting.fBodyAccJerk.meanFreq.y

sitting.fBodyAccJerk.meanFreq.z

sitting.fBodyGyro.mean.x

sitting.fBodyGyro.mean.y

sitting.fBodyGyro.mean.z

sitting.fBodyGyro.std.x

sitting.fBodyGyro.std.y

sitting.fBodyGyro.std.z

sitting.fBodyGyro.meanFreq.x

sitting.fBodyGyro.meanFreq.y

sitting.fBodyGyro.meanFreq.z

sitting.fBodyAccMag.mean

sitting.fBodyAccMag.std

sitting.fBodyAccMag.meanFreq

sitting.fBodyBodyAccJerkMag.mean

sitting.fBodyBodyAccJerkMag.std

sitting.fBodyBodyAccJerkMag.meanFreq

sitting.fBodyBodyGyroMag.mean

sitting.fBodyBodyGyroMag.std

sitting.fBodyBodyGyroMag.meanFreq

sitting.fBodyBodyGyroJerkMag.mean

sitting.fBodyBodyGyroJerkMag.std

sitting.fBodyBodyGyroJerkMag.meanFreq

sitting.angleVtBodyAccMeanBYgravityMean

sitting.angleVtBodyAccJerkMeanBYgravityMean

sitting.angleVtBodyGyroMeanBYgravityMean

sitting.angleVtBodyGyroJerkMeanBYgravityMean

sitting.angleVxBYgravityMean

sitting.angleVyBYgravityMean

sitting.angleVzBYgravityMean

standing.tBodyAcc.mean.x

standing.tBodyAcc.mean.y

standing.tBodyAcc.mean.z

standing.tBodyAcc.std.x

standing.tBodyAcc.std.y

standing.tBodyAcc.std.z

standing.tGravityAcc.mean.x

standing.tGravityAcc.mean.y

standing.tGravityAcc.mean.z

standing.tGravityAcc.std.x

standing.tGravityAcc.std.y

standing.tGravityAcc.std.z

standing.tBodyAccJerk.mean.x

standing.tBodyAccJerk.mean.y

standing.tBodyAccJerk.mean.z

standing.tBodyAccJerk.std.x

standing.tBodyAccJerk.std.y

standing.tBodyAccJerk.std.z

standing.tBodyGyro.mean.x

standing.tBodyGyro.mean.y

standing.tBodyGyro.mean.z

standing.tBodyGyro.std.x

standing.tBodyGyro.std.y

standing.tBodyGyro.std.z

standing.tBodyGyroJerk.mean.x

standing.tBodyGyroJerk.mean.y

standing.tBodyGyroJerk.mean.z

standing.tBodyGyroJerk.std.x

standing.tBodyGyroJerk.std.y

standing.tBodyGyroJerk.std.z

standing.tBodyAccMag.mean

standing.tBodyAccMag.std

standing.tGravityAccMag.mean

standing.tGravityAccMag.std

standing.tBodyAccJerkMag.mean

standing.tBodyAccJerkMag.std

standing.tBodyGyroMag.mean

standing.tBodyGyroMag.std

standing.tBodyGyroJerkMag.mean

standing.tBodyGyroJerkMag.std

standing.fBodyAcc.mean.x

standing.fBodyAcc.mean.y

standing.fBodyAcc.mean.z

standing.fBodyAcc.std.x

standing.fBodyAcc.std.y

standing.fBodyAcc.std.z

standing.fBodyAcc.meanFreq.x

standing.fBodyAcc.meanFreq.y

standing.fBodyAcc.meanFreq.z

standing.fBodyAccJerk.mean.x

standing.fBodyAccJerk.mean.y

standing.fBodyAccJerk.mean.z

standing.fBodyAccJerk.std.x

standing.fBodyAccJerk.std.y

standing.fBodyAccJerk.std.z

standing.fBodyAccJerk.meanFreq.x

standing.fBodyAccJerk.meanFreq.y

standing.fBodyAccJerk.meanFreq.z

standing.fBodyGyro.mean.x

standing.fBodyGyro.mean.y

standing.fBodyGyro.mean.z

standing.fBodyGyro.std.x

standing.fBodyGyro.std.y

standing.fBodyGyro.std.z

standing.fBodyGyro.meanFreq.x

standing.fBodyGyro.meanFreq.y

standing.fBodyGyro.meanFreq.z

standing.fBodyAccMag.mean

standing.fBodyAccMag.std

standing.fBodyAccMag.meanFreq

standing.fBodyBodyAccJerkMag.mean

standing.fBodyBodyAccJerkMag.std

standing.fBodyBodyAccJerkMag.meanFreq

standing.fBodyBodyGyroMag.mean

standing.fBodyBodyGyroMag.std

standing.fBodyBodyGyroMag.meanFreq

standing.fBodyBodyGyroJerkMag.mean

standing.fBodyBodyGyroJerkMag.std

standing.fBodyBodyGyroJerkMag.meanFreq

standing.angleVtBodyAccMeanBYgravityMean

standing.angleVtBodyAccJerkMeanBYgravityMean

standing.angleVtBodyGyroMeanBYgravityMean

standing.angleVtBodyGyroJerkMeanBYgravityMean

standing.angleVxBYgravityMean

standing.angleVyBYgravityMean

standing.angleVzBYgravityMean

laying.tBodyAcc.mean.x

laying.tBodyAcc.mean.y

laying.tBodyAcc.mean.z

laying.tBodyAcc.std.x

laying.tBodyAcc.std.y

laying.tBodyAcc.std.z

laying.tGravityAcc.mean.x

laying.tGravityAcc.mean.y

laying.tGravityAcc.mean.z

laying.tGravityAcc.std.x

laying.tGravityAcc.std.y

laying.tGravityAcc.std.z

laying.tBodyAccJerk.mean.x

laying.tBodyAccJerk.mean.y

laying.tBodyAccJerk.mean.z

laying.tBodyAccJerk.std.x

laying.tBodyAccJerk.std.y

laying.tBodyAccJerk.std.z

laying.tBodyGyro.mean.x

laying.tBodyGyro.mean.y

laying.tBodyGyro.mean.z

laying.tBodyGyro.std.x

laying.tBodyGyro.std.y

laying.tBodyGyro.std.z

laying.tBodyGyroJerk.mean.x

laying.tBodyGyroJerk.mean.y

laying.tBodyGyroJerk.mean.z

laying.tBodyGyroJerk.std.x

laying.tBodyGyroJerk.std.y

laying.tBodyGyroJerk.std.z

laying.tBodyAccMag.mean

laying.tBodyAccMag.std

laying.tGravityAccMag.mean

laying.tGravityAccMag.std

laying.tBodyAccJerkMag.mean

laying.tBodyAccJerkMag.std

laying.tBodyGyroMag.mean

laying.tBodyGyroMag.std

laying.tBodyGyroJerkMag.mean

laying.tBodyGyroJerkMag.std

laying.fBodyAcc.mean.x

laying.fBodyAcc.mean.y

laying.fBodyAcc.mean.z

laying.fBodyAcc.std.x

laying.fBodyAcc.std.y

laying.fBodyAcc.std.z

laying.fBodyAcc.meanFreq.x

laying.fBodyAcc.meanFreq.y

laying.fBodyAcc.meanFreq.z

laying.fBodyAccJerk.mean.x

laying.fBodyAccJerk.mean.y

laying.fBodyAccJerk.mean.z

laying.fBodyAccJerk.std.x

laying.fBodyAccJerk.std.y

laying.fBodyAccJerk.std.z

laying.fBodyAccJerk.meanFreq.x

laying.fBodyAccJerk.meanFreq.y

laying.fBodyAccJerk.meanFreq.z

laying.fBodyGyro.mean.x

laying.fBodyGyro.mean.y

laying.fBodyGyro.mean.z

laying.fBodyGyro.std.x

laying.fBodyGyro.std.y

laying.fBodyGyro.std.z

laying.fBodyGyro.meanFreq.x

laying.fBodyGyro.meanFreq.y

laying.fBodyGyro.meanFreq.z

laying.fBodyAccMag.mean

laying.fBodyAccMag.std

laying.fBodyAccMag.meanFreq

laying.fBodyBodyAccJerkMag.mean

laying.fBodyBodyAccJerkMag.std

laying.fBodyBodyAccJerkMag.meanFreq

laying.fBodyBodyGyroMag.mean

laying.fBodyBodyGyroMag.std

laying.fBodyBodyGyroMag.meanFreq

laying.fBodyBodyGyroJerkMag.mean

laying.fBodyBodyGyroJerkMag.std

laying.fBodyBodyGyroJerkMag.meanFreq

laying.angleVtBodyAccMeanBYgravityMean

laying.angleVtBodyAccJerkMeanBYgravityMean

laying.angleVtBodyGyroMeanBYgravityMean

laying.angleVtBodyGyroJerkMeanBYgravityMean

laying.angleVxBYgravityMean

laying.angleVyBYgravityMean

laying.angleVzBYgravityMean
