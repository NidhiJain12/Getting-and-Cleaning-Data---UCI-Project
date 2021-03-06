---
title: "README - Course Project for Getting and Cleaning Data (Coursera)"
output: html_document
---

1.Overview
---
> The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 


2.The submission contains following scripts / files
---

*  README.md - Contains information about various scripts/files and how to use them

*  CodeBook.md - It describes the variables, the raw data, and any transformations or work performed to clean up the data and the tidy data

*  Read_Test_Set.R - R Script to read the datasets provided for test data and produces a single data frame for the relevant columns for test data.

*  Read_Training_Set.R - R Script to read the datasets provided for training data and produces a single  
data frame for the relevant columns for training data.

*  run_analysis.R - R code to collect, transform, and clean the dataset and produce the tidy dataset as output. This script call the other two scripts - "Read_Test_Set.R" and "Read_Training_Set.R". It writes the output to a text file called as "tidy_data.txt" in the working directory.

*  tidy_data.txt -  Text file containing the resultant tidy dataset.

3.How to Run the code files to create the tidy dataset
---

*  Download the data files from the coursera website in your working directory.

*  Unzip the downloaded datafiles under folder "./UCI HAR Dataset" in working directory.

*  Download all the R code / script files (as mentioned in the section above) from the github account in your working directory.

*  Run the code / script "run_analysis.R". The code will automatically call other two scripts "Read_Test_Set.R" and "Read_Training_Set.R" .It will generate a tidy dataset and write to the txt file under the working directory.

*  Open the txt file in your working directory to see the tidy dataset. You can load this dataset into your R working space to analyze it further.
