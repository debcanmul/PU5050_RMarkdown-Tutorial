

ReadMe File modified from Template https://cornell.app.box.com/v/ReadmeTemplate

GENERAL INFORMATION

1. R-Tutorial
This class assessment is to create two fake data sets and then answer a question by tidying, manipulating and plotting the data.
The question created is - What is the average number of waiting days for Computer Tomography scans for each Scottish City in October 2021?

There are 2 datasets, Demographics and ImagingWaitTimes. 
The variable months in the ImagingWaitTimes; August, September and October are all from the year 2021. 
This question is to be answered by using the knowledge gained in unit PU5050 Open and Reproducible Data Science at the University of Aberdeen.

2. Author Information
	Humpty Dumpty 

3. Date of data creation
  2021-12-12

4. Location
  Aberdeen (UK)

5. Funding Sources
  N/A

SHARING/ACCESS INFORMATION

1. Licenses
  N/A

DATA & FILE OVERVIEW

1. Folder/File List: 

2021-12-02_PU5050_Input

  Fake data set created for demographics.
  2021-12-02_PU5050_Demographics.csv
  
  Fake data set created for waiting times for different imaging appointments in days for     each Scottish city.
  2021-12-02_PU5050_ImagingWaitTimes.csv

  This file is a tidied version of  2021-12-02_PU5050_Demographics.csv
  2021-12-02_PU5050_Demo_Filtered.csv

  This file is a tidied version of 2021-12-02_PU5050_ImagingWaitTimes.csv
  2021-12-12_PU5050_WaitTime_Tidy.csv
  
2021-12-02_PU5050_Method
  A copy of the RMarkdown File will be saved here.

2021-12-02_PU5050_Output
  The RMarkdown output pdf file will be saved here.

2. Version Changes
N/A

METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 
The data is a fake data set, the code was given for the data set for the creation of the data sets.

2. Methods for processing the data:

Demographics data set was tidied to remove missing values (NA) for all variables and dates beyond today's date (12/12/21) in the variable dob. The tidied data set is saved as 2021-12-02_PU5050_Demo_Filtered.csv.

ImagingWaitTimes data set was tidied to remove missing values (NA) in all variables and remove negative values or number of days greater than 365 for the variable WaitingDays. The tidied data is saved as 2021-12-12_PU5050_WaitTime_Tidy.csv.

3. Instrument- or software-specific information needed to interpret the data: 

R-Software version 4.1

Packages:
Tidyverse
here


DATA-SPECIFIC INFORMATION FOR: [2021-12-02_PU5050_Demographics]


1. Number of variables: 4

2. Number of cases/rows: 100

3. Variable List: 
See Data_Dictionary_Demographics

4. Missing data codes: 
  NA

DATA-SPECIFIC INFORMATION FOR: [2021-12-02_PU5050_ImagingWaitTimes]


1. Number of variables: 5

2. Number of cases/rows: 100

3. Variable List: 
See Data_Dictionary_ImagingWaitTimes

4. Missing data codes: 
  NA

DATA-SPECIFIC INFORMATION FOR: [2021-12-11_PU5050_Demo_Filtered]
1. Number of variable 4
2. Number of cases/rows: 94
3. Variable List:
Same variables  as Data_Dictionary_Demographics
4. Missing data codes:
The missing data has been removed from this file.

DATA-SPECIFIC INFORMATION FOR: [2021-12-12_PU5050_WaitTime_Tidy]
1. Number of variable 5
2. Number of cases/rows: 95
3. Variable List:
Same variables  as Data_Dictionary_ImagingWaitTimes
4. Missing data codes:
The missing data has been removed from this file.

COLLABORATION
GitHub - Humpty Dumpty would add the GitHub repository https address here.

CONTACT DETAILS
Humpty.Dumpty@abdn.ac.uk

SUGGESTIONS FOR FURTHER DEVELOPMENT
ImagingWaitTimes - I would have added actual dates for when the medical investigations were first requested and when the appointment was completed. Then I would have used R to calculate the number of days between the dates.
ImagingWaitTimes - I wanted to add more types of medical investigation when creating the fake data.
