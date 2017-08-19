+# Code Book
 +
 +This code book summarizes the resulting data fields in `tidy.txt`.
 +
 +## Identifiers
 +
 +* `subject` - The ID of the test subject
 +* `activity` - The type of activity performed when the corresponding measurements were taken
 +
 +## Measurements
[1] "tBodyAcc-mean()-X"                    "tBodyAcc-mean()-Y"                    "tBodyAcc-mean()-Z"                   
 [4] "tBodyAcc-std()-X"                     "tBodyAcc-std()-Y"                     "tBodyAcc-std()-Z"                    
 [7] "tGravityAcc-mean()-X"                 "tGravityAcc-mean()-Y"                 "tGravityAcc-mean()-Z"                
[10] "tGravityAcc-std()-X"                  "tGravityAcc-std()-Y"                  "tGravityAcc-std()-Z"                 
[13] "tBodyAccJerk-mean()-X"                "tBodyAccJerk-mean()-Y"                "tBodyAccJerk-mean()-Z"               
[16] "tBodyAccJerk-std()-X"                 "tBodyAccJerk-std()-Y"                 "tBodyAccJerk-std()-Z"                
[19] "tBodyGyro-mean()-X"                   "tBodyGyro-mean()-Y"                   "tBodyGyro-mean()-Z"                  
[22] "tBodyGyro-std()-X"                    "tBodyGyro-std()-Y"                    "tBodyGyro-std()-Z"                   
[25] "tBodyGyroJerk-mean()-X"               "tBodyGyroJerk-mean()-Y"               "tBodyGyroJerk-mean()-Z"              
[28] "tBodyGyroJerk-std()-X"                "tBodyGyroJerk-std()-Y"                "tBodyGyroJerk-std()-Z"               
[31] "tBodyAccMag-mean()"                   "tBodyAccMag-std()"                    "tGravityAccMag-mean()"               
[34] "tGravityAccMag-std()"                 "tBodyAccJerkMag-mean()"               "tBodyAccJerkMag-std()"               
[37] "tBodyGyroMag-mean()"                  "tBodyGyroMag-std()"                   "tBodyGyroJerkMag-mean()"             
[40] "tBodyGyroJerkMag-std()"               "fBodyAcc-mean()-X"                    "fBodyAcc-mean()-Y"                   
[43] "fBodyAcc-mean()-Z"                    "fBodyAcc-std()-X"                     "fBodyAcc-std()-Y"                    
[46] "fBodyAcc-std()-Z"                     "fBodyAcc-meanFreq()-X"                "fBodyAcc-meanFreq()-Y"               
[49] "fBodyAcc-meanFreq()-Z"                "fBodyAccJerk-mean()-X"                "fBodyAccJerk-mean()-Y"               
[52] "fBodyAccJerk-mean()-Z"                "fBodyAccJerk-std()-X"                 "fBodyAccJerk-std()-Y"                
[55] "fBodyAccJerk-std()-Z"                 "fBodyAccJerk-meanFreq()-X"            "fBodyAccJerk-meanFreq()-Y"           
[58] "fBodyAccJerk-meanFreq()-Z"            "fBodyGyro-mean()-X"                   "fBodyGyro-mean()-Y"                  
[61] "fBodyGyro-mean()-Z"                   "fBodyGyro-std()-X"                    "fBodyGyro-std()-Y"                   
[64] "fBodyGyro-std()-Z"                    "fBodyGyro-meanFreq()-X"               "fBodyGyro-meanFreq()-Y"              
[67] "fBodyGyro-meanFreq()-Z"               "fBodyAccMag-mean()"                   "fBodyAccMag-std()"                   
[70] "fBodyAccMag-meanFreq()"               "fBodyBodyAccJerkMag-mean()"           "fBodyBodyAccJerkMag-std()"           
[73] "fBodyBodyAccJerkMag-meanFreq()"       "fBodyBodyGyroMag-mean()"              "fBodyBodyGyroMag-std()"              
[76] "fBodyBodyGyroMag-meanFreq()"          "fBodyBodyGyroJerkMag-mean()"          "fBodyBodyGyroJerkMag-std()"          
[79] "fBodyBodyGyroJerkMag-meanFreq()"      "angle(tBodyAccMean,gravity)"          "angle(tBodyAccJerkMean),gravityMean)"
[82] "angle(tBodyGyroMean,gravityMean)"     "angle(tBodyGyroJerkMean,gravityMean)" "angle(X,gravityMean)"                
[85] "angle(Y,gravityMean)"                 "angle(Z,gravityMean)"
 
 ## Activity Labels
 
 +* `WALKING` (value `1`): subject was walking during the test
 +* `WALKING_UPSTAIRS` (value `2`): subject was walking up a staircase during the test
 +* `WALKING_DOWNSTAIRS` (value `3`): subject was walking down a staircase during the test
 +* `SITTING` (value `4`): subject was sitting during the test
 +* `STANDING` (value `5`): subject was standing during the test
 +* `LAYING` (value `6`): subject was laying down during the test
