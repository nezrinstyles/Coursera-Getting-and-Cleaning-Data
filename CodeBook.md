This code book describes the variables and transformations applied in the tidy dataset.

## Variables
1. **subject**: Identifier for the subject (1-30).
2. **activity**: The activity performed (e.g., "WALKING", "SITTING").
3. **TimeBodyAccelerometer-mean()-X**: Mean value of body acceleration along the X-axis.
4. **FrequencyBodyGyroscope-std()-Z**: Standard deviation of gyroscopic measurements in the Z-axis.

## Transformations
1. Merged training and test datasets.
2. Extracted mean and standard deviation measurements.
3. Renamed variables for clarity.
4. Created a second dataset with averages for each activity and subject.
