# Personal Informatics - Step Count Analysis and Adherence

## Driving Question
Driving Question 1: Did I achieve my goal of X steps more in the last 12 months than the 12 months before that?

Driving Question 2: Do I have more steps on average during the weekend in comparison to a weekday?

## Introduction
The purpose of this project is to answer the driving question; did Person 1 or Person 2 achieve X amount of steps more in the past 12 months compared to the 12 months before that. Analysis was performed on the two data sets provided, to determine if each person achieved their target. Cleaning the data sets, aggregation methods (day, month step countss), and advanced visual techniques were deployed to analyze and answer the first driving question.

The second driving question was to determine if Person 1 or Person 2 walked more steps on a weekend rather than on a weekday. The hypothesis made was that people will generally be more physically active on the weekend, rather than on a weekday; therefore, the second driving question was to analyse the data sets to prove or disprove this hypothesis.

## Project Team Members
1. Benjamin Boey, 480066938
2. Benjamin Teo, 490580833
3. Gerry How
4. James Park
5. Timothy D'cruz

## Table of Contents

### Key Files
1. Product Notebook
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Product%20Notebook.ipynb
2. Raw Data
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/tree/master/src/data

### Key Variables
1. df1_raw - Data frame for person 1 imported from the raw data.

2. df2_raw - Data frame for person 2 imported from the raw data.

3. df1 - Data frame for person 1 with converted time column into date/time format.

4. df2 - Data frame for person 2 with converted time column into date/time format.

5. test_df - A dummy variable with constant steps for testing.

6. cleaned_1 - Data set for person 1 where data points for daily accrual of steps exceed 40000 which the group unanimously concurred as outliers. This data frame will be used for final analysis and visualisations.

7. cleaned_2 - Data set for person 2 where data points for daily accrual of steps exceed 40000 which the group unanimously concurred as outliers. This data frame will be used for final analysis and visualisations.

### Wiki Links
1. Home Page
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki
2. Group Roles
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Group-Roles
3. Group Contract Details
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Group-Contract
4. Slide Task Assignments
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Assignment-Roles-for-Presentation
5. Link to Video Presentation
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Assignment-Video-link
6. Link to Presentation Slides
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Presentation-Slides
7. Benjamin Boey Weekly Work Update
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Benjamin-Boey
8. Benjamin Teo Weekly Work Update
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Benjamin-Teo-Research
9. Timothy D'Cruz Weekly Work Update
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Timothy-D'Cruz
10. Gerry How Weekly Work Update
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Gerry-How--Findings
11. James Park Weekly Work Update
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Week-10-Summary-James-Park
12. Code Review Page
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Code-Review--
13. Meeting Minutes
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Meeting-Minutes-Taker
14. Think Aloud Summary
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Think-aloud-Cognitive-Walkthrough
15. Retrospective
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/wiki/Retrospective

### Code Pages

#### Gerry How Process Notebooks
1. Initial Analysis - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/EDA%20week%207/Week08_GerryHow_DATA3406_EDA.ipynb
2. Exploration of Driving Question - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Week%209/12%20month%20exploration.ipynb
3. Visualisations - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Week%2010/Results%20plotting.ipynb

#### Benjamin Boey Process Notebooks
1. Full Process Notebook - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Boey-EDA/Process%20notebook.ipynb

#### Timothy D'Cruz Process Notebooks
1. Data Exploration and Preliminary Analysis - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Week%208%20Mini%20Assignment%20-%20Timothy%20D'Cruz.ipynb
2. Further Exploration of Data and Analysis - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Week%2010%20Mini%20Assignment%20-%20Timothy.ipynb

#### James Park Process Notebooks
1. Exploratory Data Analysis - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Week08%20IDA%20James%20Park.ipynb
2. Further Exploration Into Relationship Between Variables - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Week09.ipynb
3. Analysis for Second Driving Question - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Week10%20-%20James%20Park.ipynb
4. Further Analysis and Visualisations for Second Driving Question - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Week11%20-%20James%20Park.ipynb

#### Benjamin Teo Process Notebooks
1. Preliminary Data Exploration and Analysis - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Week08-BenjaminTeo-Exploration/Week08-BenjaminTeo-Exploration.ipynb
2. Analysis into Step Count Sources - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Week08-BenjaminTeo-Exploration/Source%20Step%20Count%20Analysis.ipynb
3. Analysis About Uncertainty of Raw Data and Step Count Duplicates with Visualisations - 
https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/blob/master/src/Week08-BenjaminTeo-Exploration/Week10-Benjamin%20Teo-Source%20Step%20Count%20Analysis.ipynb

### Issues
1. Data Exploration - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/1
2. Analysis of Assignment - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/2
3. Start Constructing Readme File - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/4
4. Initial Data Analysis - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/5
5. Pattern Finding in Data - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/5
6. Data Exploration - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/6
7. Exploration of Variables by Date - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/7
8. Explore Person 1 Data Sources - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/10
9. Further Analysis of Data for Person 1 Sources - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/11
10. Visualisations for Driving Question 1 - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/12
11. Report Planning - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/13
12. Driving Question 2 Analysis and Results - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/16
13. Confirm Uncertainty Element - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/17
14. Process Notebook Review - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/19
15. Slides for Driving Question - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/21
16. Analysis for Driving Question - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/24
17. Visualisation Beautification - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/25
18. Presentation Script - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/26
19. Data Visuals - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/3
20. Create and Define Driving Question - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/8
21. Removal of Outliers - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/9
22. Data Set Cleaning - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/14
23. Define Step Goal - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/15
24. Edit and Proofread Readme - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/18
25. Code Testing - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/20
26. Record Presentation - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/22
27. Product Notebook Compilation - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/23
28. Record Ethics Section of Presentation - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/27
29. Collate Video Presentation - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/28
30. Review and Upload Video - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/29
31. Review Literate Programming - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/30
32. Tracking Document Review - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/31
33. Write-up for Driving Question 2 - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/32
34. Retrospective Wiki Page - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/33
35. Think Aloud Wiki Page - https://github.sydney.edu.au/YHOW4819/2021-DATA3406-PRAC07-Group04/issues/34
