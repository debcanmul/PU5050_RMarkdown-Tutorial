

ReadMe File modified from Template https://cornell.app.box.com/v/ReadmeTemplate

GENERAL INFORMATION

1. R-Tutorial
ADD SCENARIO

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


DATA-SPECIFIC INFORMATION FOR: [FILENAME]
<repeat this section for each dataset, folder or file, as appropriate>

1. Number of variables: 

2. Number of cases/rows: 

3. Variable List: 
<list variable name(s), description(s), unit(s)and value labels as appropriate for each>

4. Missing data codes: 
  NA

COLLABORATION
GitHub - Humpty Dumpty would add the GitHub repository https address here.

CONTACT DETAILS
Humpty.Dumpty@abdn.ac.uk

SUGGESTIONS FOR FURTHER DEVELOPMENT
