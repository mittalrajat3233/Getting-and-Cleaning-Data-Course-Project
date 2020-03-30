# Getting-and-Cleaning-Data-Course-Project
@@ -18,3 +18,18 @@ https://www.coursera.org/course/getdata
>* Uses descriptive activity names to name the activities in the data set
>* Appropriately labels the data set with descriptive variable names. 
>* Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
## Executing

### install packages 
* RCurl
* reshape2

### set working dir
* Script creates a relative `./data` dir in which it downloads the .zip, extracts it and writes the result file (`tidy_data.txt`)

### run `run_analysis.R`
* writes data to `./data` dir
* generates/overwrites `./CodeBook.md`
* `source('run_analysis.R')`
* global variables `tidyData` & `resultData` (see `CodeBook.md`)
