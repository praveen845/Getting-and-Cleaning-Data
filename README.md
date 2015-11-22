---
title: "Getting and Cleaning Data - Course Project"

date: "22 November 2015"
output: html_document
---

We will store the R Code and the documentation for the 'Getting and Cleaning Data" module's project in this repository. 

We will source the data from:  [Human Activity Recognition Using Smart Phones](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip).

The R script, `run_analysis.R`, when executed will perform the below steps:

1. It downloads the above mentioned data if it is not already existing in the working directory.

2. It loads the activity tables and the features.

3. It loads the two datasets `training` and `test` keeping only those columns which reflect mean or standard deviation.

4. It loads the activity and subject data for each dataset and merges those columns with the dataset.

5. It then merges the two datasets.

6. After that it converts the `activity` and `subject` columns into factors.

7. Finally it creates a tidy dataset that has the average value of each variable for each subject and activity pair.


The final result is then stored in the `tidy.txt` dataset.

In addition to the above R script and the tidy dataset, we will include the following:

1. The `README.md` markdown file that explains how the script works and what other files are included in this repository.

2. The `CodeBook.md` markdown file that describes the variables, the data and the transformations/work that is performed to clean up the data.

##Thank You!!