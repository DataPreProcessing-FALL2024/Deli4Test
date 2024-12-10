# Deli4Test

## This is my fourth deliverable.
The aggregation code was done in R Studio and used the Real Estate cleaned and formatted dataset that can be found at- 
https://github.com/DataPreProcessing-FALL2024/Deli2Test/raw/refs/heads/main/DataCleanAndFormatted/Formatted_Real_Estate_Data.RDS. 

You can see the aggregation code here- https://datapreprocessing-fall2024.github.io/Deli4Test/.

## Aggregation Steps

First, I loaded in the data set from Github and only kept columns of interest.

### **1 Group, 1 Function, 1 Input Variable**

For this section, I looked at mean square footage by location.


Group- Location

Input Variable- Size in Square Feet

Function- Mean


After aggregating, I saved the output to an RDS file (output111.rds) within the 'finalOutput' folder.


### **2 Groups, 2 Functions, 1 Input Variable**

For this section, I looked at mean and median price in BDT by location and whether or not the space is furnished.


Groups- Location, Furnished

Input Variable- Price in BDT

Functions- Mean, Median


After aggregating, I saved the output to an RDS file (output221.rds) within the 'finalOutput' folder.


### **1 Group, 2 Input Variables, Different Function For Each**

For this section, I looked at the mean price and median size in square feet by the year the space was built.


Group- Year built

Input Variables- Price in BDT, Size in Square Feet

Functions- Mean for Price variable Median for Size variable

After aggregating, I saved the output to an RDS file (output12f1f2.rds) within the 'finalOutput' folder.
After aggregating, I saved the output to an RDS file.
