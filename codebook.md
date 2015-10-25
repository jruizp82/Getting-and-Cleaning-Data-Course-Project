---
title: "codebook.md"
author: "Juan Antonio Ruiz"
date: "25 de octubre de 2015"
output: html_document
---


## Project Description
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

##Study design and data processing

###Collection of the raw data
The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

##Creating the tidy datafile

###Guide to create the tidy data file
1.Download the file and put the file in the data folder
2.Merges the training and the test sets to create one data set.
3.Extracts only the measurements on the mean and standard deviation for each measurement.
4.Uses descriptive activity names to name the activities in the data set
5.Appropriately labels the data set with descriptive variable names.
6.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

##Description of the variables in the tiny_data.txt file
General description of the file including:
 - Dimensions of the dataset
   [1] 180  68
 - Summary of the data
   summary(Data2)
    subject                   activity  timeBodyAccelerometer-mean()-X
 Min.   : 1.0   WALKING           :30   Min.   :0.2216                
 1st Qu.: 8.0   WALKING_UPSTAIRS  :30   1st Qu.:0.2712                
 Median :15.5   WALKING_DOWNSTAIRS:30   Median :0.2770                
 Mean   :15.5   SITTING           :30   Mean   :0.2743                
 3rd Qu.:23.0   STANDING          :30   3rd Qu.:0.2800                
 Max.   :30.0   LAYING            :30   Max.   :0.3015                
 timeBodyAccelerometer-mean()-Y timeBodyAccelerometer-mean()-Z
 Min.   :-0.040514              Min.   :-0.15251              
 1st Qu.:-0.020022              1st Qu.:-0.11207              
 Median :-0.017262              Median :-0.10819              
 Mean   :-0.017876              Mean   :-0.10916              
 3rd Qu.:-0.014936              3rd Qu.:-0.10443              
 Max.   :-0.001308              Max.   :-0.07538              
 timeBodyAccelerometer-std()-X timeBodyAccelerometer-std()-Y
 Min.   :-0.9961               Min.   :-0.99024             
 1st Qu.:-0.9799               1st Qu.:-0.94205             
 Median :-0.7526               Median :-0.50897             
 Mean   :-0.5577               Mean   :-0.46046             
 3rd Qu.:-0.1984               3rd Qu.:-0.03077             
 Max.   : 0.6269               Max.   : 0.61694             
 timeBodyAccelerometer-std()-Z timeGravityAccelerometer-mean()-X
 Min.   :-0.9877               Min.   :-0.6800                  
 1st Qu.:-0.9498               1st Qu.: 0.8376                  
 Median :-0.6518               Median : 0.9208                  
 Mean   :-0.5756               Mean   : 0.6975                  
 3rd Qu.:-0.2306               3rd Qu.: 0.9425                  
 Max.   : 0.6090               Max.   : 0.9745                  
 timeGravityAccelerometer-mean()-Y timeGravityAccelerometer-mean()-Z
 Min.   :-0.47989                  Min.   :-0.49509                 
 1st Qu.:-0.23319                  1st Qu.:-0.11726                 
 Median :-0.12782                  Median : 0.02384                 
 Mean   :-0.01621                  Mean   : 0.07413                 
 3rd Qu.: 0.08773                  3rd Qu.: 0.14946                 
 Max.   : 0.95659                  Max.   : 0.95787                 
 timeGravityAccelerometer-std()-X timeGravityAccelerometer-std()-Y
 Min.   :-0.9968                  Min.   :-0.9942                 
 1st Qu.:-0.9825                  1st Qu.:-0.9711                 
 Median :-0.9695                  Median :-0.9590                 
 Mean   :-0.9638                  Mean   :-0.9524                 
 3rd Qu.:-0.9509                  3rd Qu.:-0.9370                 
 Max.   :-0.8296                  Max.   :-0.6436                 
 timeGravityAccelerometer-std()-Z timeBodyAccelerometerJerk-mean()-X
 Min.   :-0.9910                  Min.   :0.04269                   
 1st Qu.:-0.9605                  1st Qu.:0.07396                   
 Median :-0.9450                  Median :0.07640                   
 Mean   :-0.9364                  Mean   :0.07947                   
 3rd Qu.:-0.9180                  3rd Qu.:0.08330                   
 Max.   :-0.6102                  Max.   :0.13019                   
 timeBodyAccelerometerJerk-mean()-Y timeBodyAccelerometerJerk-mean()-Z
 Min.   :-0.0386872                 Min.   :-0.067458                 
 1st Qu.: 0.0004664                 1st Qu.:-0.010601                 
 Median : 0.0094698                 Median :-0.003861                 
 Mean   : 0.0075652                 Mean   :-0.004953                 
 3rd Qu.: 0.0134008                 3rd Qu.: 0.001958                 
 Max.   : 0.0568186                 Max.   : 0.038053                 
 timeBodyAccelerometerJerk-std()-X timeBodyAccelerometerJerk-std()-Y
 Min.   :-0.9946                   Min.   :-0.9895                  
 1st Qu.:-0.9832                   1st Qu.:-0.9724                  
 Median :-0.8104                   Median :-0.7756                  
 Mean   :-0.5949                   Mean   :-0.5654                  
 3rd Qu.:-0.2233                   3rd Qu.:-0.1483                  
 Max.   : 0.5443                   Max.   : 0.3553                  
 timeBodyAccelerometerJerk-std()-Z timeBodyGyroscope-mean()-X timeBodyGyroscope-mean()-Y
 Min.   :-0.99329                  Min.   :-0.20578           Min.   :-0.20421          
 1st Qu.:-0.98266                  1st Qu.:-0.04712           1st Qu.:-0.08955          
 Median :-0.88366                  Median :-0.02871           Median :-0.07318          
 Mean   :-0.73596                  Mean   :-0.03244           Mean   :-0.07426          
 3rd Qu.:-0.51212                  3rd Qu.:-0.01676           3rd Qu.:-0.06113          
 Max.   : 0.03102                  Max.   : 0.19270           Max.   : 0.02747          
 timeBodyGyroscope-mean()-Z timeBodyGyroscope-std()-X timeBodyGyroscope-std()-Y
 Min.   :-0.07245           Min.   :-0.9943           Min.   :-0.9942          
 1st Qu.: 0.07475           1st Qu.:-0.9735           1st Qu.:-0.9629          
 Median : 0.08512           Median :-0.7890           Median :-0.8017          
 Mean   : 0.08744           Mean   :-0.6916           Mean   :-0.6533          
 3rd Qu.: 0.10177           3rd Qu.:-0.4414           3rd Qu.:-0.4196          
 Max.   : 0.17910           Max.   : 0.2677           Max.   : 0.4765          
 timeBodyGyroscope-std()-Z timeBodyGyroscopeJerk-mean()-X timeBodyGyroscopeJerk-mean()-Y
 Min.   :-0.9855           Min.   :-0.15721               Min.   :-0.07681              
 1st Qu.:-0.9609           1st Qu.:-0.10322               1st Qu.:-0.04552              
 Median :-0.8010           Median :-0.09868               Median :-0.04112              
 Mean   :-0.6164           Mean   :-0.09606               Mean   :-0.04269              
 3rd Qu.:-0.3106           3rd Qu.:-0.09110               3rd Qu.:-0.03842              
 Max.   : 0.5649           Max.   :-0.02209               Max.   :-0.01320              
 timeBodyGyroscopeJerk-mean()-Z timeBodyGyroscopeJerk-std()-X
 Min.   :-0.092500              Min.   :-0.9965              
 1st Qu.:-0.061725              1st Qu.:-0.9800              
 Median :-0.053430              Median :-0.8396              
 Mean   :-0.054802              Mean   :-0.7036              
 3rd Qu.:-0.048985              3rd Qu.:-0.4629              
 Max.   :-0.006941              Max.   : 0.1791              
 timeBodyGyroscopeJerk-std()-Y timeBodyGyroscopeJerk-std()-Z
 Min.   :-0.9971               Min.   :-0.9954              
 1st Qu.:-0.9832               1st Qu.:-0.9848              
 Median :-0.8942               Median :-0.8610              
 Mean   :-0.7636               Mean   :-0.7096              
 3rd Qu.:-0.5861               3rd Qu.:-0.4741              
 Max.   : 0.2959               Max.   : 0.1932              
 timeBodyAccelerometerMagnitude-mean() timeBodyAccelerometerMagnitude-std()
 Min.   :-0.9865                       Min.   :-0.9865                     
 1st Qu.:-0.9573                       1st Qu.:-0.9430                     
 Median :-0.4829                       Median :-0.6074                     
 Mean   :-0.4973                       Mean   :-0.5439                     
 3rd Qu.:-0.0919                       3rd Qu.:-0.2090                     
 Max.   : 0.6446                       Max.   : 0.4284                     
 timeGravityAccelerometerMagnitude-mean() timeGravityAccelerometerMagnitude-std()
 Min.   :-0.9865                          Min.   :-0.9865                        
 1st Qu.:-0.9573                          1st Qu.:-0.9430                        
 Median :-0.4829                          Median :-0.6074                        
 Mean   :-0.4973                          Mean   :-0.5439                        
 3rd Qu.:-0.0919                          3rd Qu.:-0.2090                        
 Max.   : 0.6446                          Max.   : 0.4284                        
 timeBodyAccelerometerJerkMagnitude-mean() timeBodyAccelerometerJerkMagnitude-std()
 Min.   :-0.9928                           Min.   :-0.9946                         
 1st Qu.:-0.9807                           1st Qu.:-0.9765                         
 Median :-0.8168                           Median :-0.8014                         
 Mean   :-0.6079                           Mean   :-0.5842                         
 3rd Qu.:-0.2456                           3rd Qu.:-0.2173                         
 Max.   : 0.4345                           Max.   : 0.4506                         
 timeBodyGyroscopeMagnitude-mean() timeBodyGyroscopeMagnitude-std()
 Min.   :-0.9807                   Min.   :-0.9814                 
 1st Qu.:-0.9461                   1st Qu.:-0.9476                 
 Median :-0.6551                   Median :-0.7420                 
 Mean   :-0.5652                   Mean   :-0.6304                 
 3rd Qu.:-0.2159                   3rd Qu.:-0.3602                 
 Max.   : 0.4180                   Max.   : 0.3000                 
 timeBodyGyroscopeJerkMagnitude-mean() timeBodyGyroscopeJerkMagnitude-std()
 Min.   :-0.99732                      Min.   :-0.9977                     
 1st Qu.:-0.98515                      1st Qu.:-0.9805                     
 Median :-0.86479                      Median :-0.8809                     
 Mean   :-0.73637                      Mean   :-0.7550                     
 3rd Qu.:-0.51186                      3rd Qu.:-0.5767                     
 Max.   : 0.08758                      Max.   : 0.2502                     
 frequencyBodyAccelerometer-mean()-X frequencyBodyAccelerometer-mean()-Y
 Min.   :-0.9952                     Min.   :-0.98903                   
 1st Qu.:-0.9787                     1st Qu.:-0.95361                   
 Median :-0.7691                     Median :-0.59498                   
 Mean   :-0.5758                     Mean   :-0.48873                   
 3rd Qu.:-0.2174                     3rd Qu.:-0.06341                   
 Max.   : 0.5370                     Max.   : 0.52419                   
 frequencyBodyAccelerometer-mean()-Z frequencyBodyAccelerometer-std()-X
 Min.   :-0.9895                     Min.   :-0.9966                   
 1st Qu.:-0.9619                     1st Qu.:-0.9820                   
 Median :-0.7236                     Median :-0.7470                   
 Mean   :-0.6297                     Mean   :-0.5522                   
 3rd Qu.:-0.3183                     3rd Qu.:-0.1966                   
 Max.   : 0.2807                     Max.   : 0.6585                   
 frequencyBodyAccelerometer-std()-Y frequencyBodyAccelerometer-std()-Z
 Min.   :-0.99068                   Min.   :-0.9872                   
 1st Qu.:-0.94042                   1st Qu.:-0.9459                   
 Median :-0.51338                   Median :-0.6441                   
 Mean   :-0.48148                   Mean   :-0.5824                   
 3rd Qu.:-0.07913                   3rd Qu.:-0.2655                   
 Max.   : 0.56019                   Max.   : 0.6871                   
 frequencyBodyAccelerometerJerk-mean()-X frequencyBodyAccelerometerJerk-mean()-Y
 Min.   :-0.9946                         Min.   :-0.9894                        
 1st Qu.:-0.9828                         1st Qu.:-0.9725                        
 Median :-0.8126                         Median :-0.7817                        
 Mean   :-0.6139                         Mean   :-0.5882                        
 3rd Qu.:-0.2820                         3rd Qu.:-0.1963                        
 Max.   : 0.4743                         Max.   : 0.2767                        
 frequencyBodyAccelerometerJerk-mean()-Z frequencyBodyAccelerometerJerk-std()-X
 Min.   :-0.9920                         Min.   :-0.9951                       
 1st Qu.:-0.9796                         1st Qu.:-0.9847                       
 Median :-0.8707                         Median :-0.8254                       
 Mean   :-0.7144                         Mean   :-0.6121                       
 3rd Qu.:-0.4697                         3rd Qu.:-0.2475                       
 Max.   : 0.1578                         Max.   : 0.4768                       
 frequencyBodyAccelerometerJerk-std()-Y frequencyBodyAccelerometerJerk-std()-Z
 Min.   :-0.9905                        Min.   :-0.993108                     
 1st Qu.:-0.9737                        1st Qu.:-0.983747                     
 Median :-0.7852                        Median :-0.895121                     
 Mean   :-0.5707                        Mean   :-0.756489                     
 3rd Qu.:-0.1685                        3rd Qu.:-0.543787                     
 Max.   : 0.3498                        Max.   :-0.006236                     
 frequencyBodyGyroscope-mean()-X frequencyBodyGyroscope-mean()-Y
 Min.   :-0.9931                 Min.   :-0.9940                
 1st Qu.:-0.9697                 1st Qu.:-0.9700                
 Median :-0.7300                 Median :-0.8141                
 Mean   :-0.6367                 Mean   :-0.6767                
 3rd Qu.:-0.3387                 3rd Qu.:-0.4458                
 Max.   : 0.4750                 Max.   : 0.3288                
 frequencyBodyGyroscope-mean()-Z frequencyBodyGyroscope-std()-X
 Min.   :-0.9860                 Min.   :-0.9947               
 1st Qu.:-0.9624                 1st Qu.:-0.9750               
 Median :-0.7909                 Median :-0.8086               
 Mean   :-0.6044                 Mean   :-0.7110               
 3rd Qu.:-0.2635                 3rd Qu.:-0.4813               
 Max.   : 0.4924                 Max.   : 0.1966               
 frequencyBodyGyroscope-std()-Y frequencyBodyGyroscope-std()-Z
 Min.   :-0.9944                Min.   :-0.9867               
 1st Qu.:-0.9602                1st Qu.:-0.9643               
 Median :-0.7964                Median :-0.8224               
 Mean   :-0.6454                Mean   :-0.6577               
 3rd Qu.:-0.4154                3rd Qu.:-0.3916               
 Max.   : 0.6462                Max.   : 0.5225               
 frequencyBodyAccelerometerMagnitude-mean() frequencyBodyAccelerometerMagnitude-std()
 Min.   :-0.9868                            Min.   :-0.9876                          
 1st Qu.:-0.9560                            1st Qu.:-0.9452                          
 Median :-0.6703                            Median :-0.6513                          
 Mean   :-0.5365                            Mean   :-0.6210                          
 3rd Qu.:-0.1622                            3rd Qu.:-0.3654                          
 Max.   : 0.5866                            Max.   : 0.1787                          
 frequencyBodyAccelerometerJerkMagnitude-mean()
 Min.   :-0.9940                               
 1st Qu.:-0.9770                               
 Median :-0.7940                               
 Mean   :-0.5756                               
 3rd Qu.:-0.1872                               
 Max.   : 0.5384                               
 frequencyBodyAccelerometerJerkMagnitude-std() frequencyBodyGyroscopeMagnitude-mean()
 Min.   :-0.9944                               Min.   :-0.9865                       
 1st Qu.:-0.9752                               1st Qu.:-0.9616                       
 Median :-0.8126                               Median :-0.7657                       
 Mean   :-0.5992                               Mean   :-0.6671                       
 3rd Qu.:-0.2668                               3rd Qu.:-0.4087                       
 Max.   : 0.3163                               Max.   : 0.2040                       
 frequencyBodyGyroscopeMagnitude-std() frequencyBodyGyroscopeJerkMagnitude-mean()
 Min.   :-0.9815                       Min.   :-0.9976                           
 1st Qu.:-0.9488                       1st Qu.:-0.9813                           
 Median :-0.7727                       Median :-0.8779                           
 Mean   :-0.6723                       Mean   :-0.7564                           
 3rd Qu.:-0.4277                       3rd Qu.:-0.5831                           
 Max.   : 0.2367                       Max.   : 0.1466                           
 frequencyBodyGyroscopeJerkMagnitude-std()
 Min.   :-0.9976                          
 1st Qu.:-0.9802                          
 Median :-0.8941                          
 Mean   :-0.7715                          
 3rd Qu.:-0.6081                          
 Max.   : 0.2878 
   
 - Variables present in the dataset
   names(Data2)
   [1] "subject"                                       
 [2] "activity"                                      
 [3] "timeBodyAccelerometer-mean()-X"                
 [4] "timeBodyAccelerometer-mean()-Y"                
 [5] "timeBodyAccelerometer-mean()-Z"                
 [6] "timeBodyAccelerometer-std()-X"                 
 [7] "timeBodyAccelerometer-std()-Y"                 
 [8] "timeBodyAccelerometer-std()-Z"                 
 [9] "timeGravityAccelerometer-mean()-X"             
[10] "timeGravityAccelerometer-mean()-Y"             
[11] "timeGravityAccelerometer-mean()-Z"             
[12] "timeGravityAccelerometer-std()-X"              
[13] "timeGravityAccelerometer-std()-Y"              
[14] "timeGravityAccelerometer-std()-Z"              
[15] "timeBodyAccelerometerJerk-mean()-X"            
[16] "timeBodyAccelerometerJerk-mean()-Y"            
[17] "timeBodyAccelerometerJerk-mean()-Z"            
[18] "timeBodyAccelerometerJerk-std()-X"             
[19] "timeBodyAccelerometerJerk-std()-Y"             
[20] "timeBodyAccelerometerJerk-std()-Z"             
[21] "timeBodyGyroscope-mean()-X"                    
[22] "timeBodyGyroscope-mean()-Y"                    
[23] "timeBodyGyroscope-mean()-Z"                    
[24] "timeBodyGyroscope-std()-X"                     
[25] "timeBodyGyroscope-std()-Y"                     
[26] "timeBodyGyroscope-std()-Z"                     
[27] "timeBodyGyroscopeJerk-mean()-X"                
[28] "timeBodyGyroscopeJerk-mean()-Y"                
[29] "timeBodyGyroscopeJerk-mean()-Z"                
[30] "timeBodyGyroscopeJerk-std()-X"                 
[31] "timeBodyGyroscopeJerk-std()-Y"                 
[32] "timeBodyGyroscopeJerk-std()-Z"                 
[33] "timeBodyAccelerometerMagnitude-mean()"         
[34] "timeBodyAccelerometerMagnitude-std()"          
[35] "timeGravityAccelerometerMagnitude-mean()"      
[36] "timeGravityAccelerometerMagnitude-std()"       
[37] "timeBodyAccelerometerJerkMagnitude-mean()"     
[38] "timeBodyAccelerometerJerkMagnitude-std()"      
[39] "timeBodyGyroscopeMagnitude-mean()"             
[40] "timeBodyGyroscopeMagnitude-std()"              
[41] "timeBodyGyroscopeJerkMagnitude-mean()"         
[42] "timeBodyGyroscopeJerkMagnitude-std()"          
[43] "frequencyBodyAccelerometer-mean()-X"           
[44] "frequencyBodyAccelerometer-mean()-Y"           
[45] "frequencyBodyAccelerometer-mean()-Z"           
[46] "frequencyBodyAccelerometer-std()-X"            
[47] "frequencyBodyAccelerometer-std()-Y"            
[48] "frequencyBodyAccelerometer-std()-Z"            
[49] "frequencyBodyAccelerometerJerk-mean()-X"       
[50] "frequencyBodyAccelerometerJerk-mean()-Y"       
[51] "frequencyBodyAccelerometerJerk-mean()-Z"       
[52] "frequencyBodyAccelerometerJerk-std()-X"        
[53] "frequencyBodyAccelerometerJerk-std()-Y"        
[54] "frequencyBodyAccelerometerJerk-std()-Z"        
[55] "frequencyBodyGyroscope-mean()-X"               
[56] "frequencyBodyGyroscope-mean()-Y"               
[57] "frequencyBodyGyroscope-mean()-Z"               
[58] "frequencyBodyGyroscope-std()-X"                
[59] "frequencyBodyGyroscope-std()-Y"                
[60] "frequencyBodyGyroscope-std()-Z"                
[61] "frequencyBodyAccelerometerMagnitude-mean()"    
[62] "frequencyBodyAccelerometerMagnitude-std()"     
[63] "frequencyBodyAccelerometerJerkMagnitude-mean()"
[64] "frequencyBodyAccelerometerJerkMagnitude-std()" 
[65] "frequencyBodyGyroscopeMagnitude-mean()"        
[66] "frequencyBodyGyroscopeMagnitude-std()"         
[67] "frequencyBodyGyroscopeJerkMagnitude-mean()"    
[68] "frequencyBodyGyroscopeJerkMagnitude-std()"


