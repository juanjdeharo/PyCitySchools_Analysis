# PyCitySchools_Analysis

## Overview of Analysis
> After performing the school district analysis it was believed there may be a problem with the test scores for Thomas High School ninth graders. Therefore I was tasked with:
1. Changing those test scores to "NaN" and 
2. Then re-running the PyCitySchools analysis as well as an analysis of Thomas High School

## Resources
> Data Source: schools_complete.csv, schools_complete.csv
> Software: Pandas, Jupyter Notebook

## Results:

### Proof of re-creating the students dataframe while replacing all test scores for ninth graders in Thomas High School with "NaN":

![Thomas High School ninth grade test scores nulled](https://github.com/juanjdeharo/PyCitySchools_Analysis/blob/main/student_df.PNG)

### How was the district summary affected:
![New District Summary](https://github.com/juanjdeharo/PyCitySchools_Analysis/blob/main/new_district_summary_df.PNG)
> There is honestly barely any difference 

### How was the Thomas High School summary affected?
![New District Summary](https://github.com/juanjdeharo/PyCitySchools_Analysis/blob/main/thomas_high_analysis.PNG)	
> The passing rates were much higher than the overall passing rates. Also I was unable to format School Type or Per Student Budget Correctly
