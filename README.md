# School District Analysis

## Overview
A school board requested an analysis of local high schools. The primary measure of a school's success was math and reading scores to inform high and low performing schools, and compare average scores by grade, school spending, student population size, and school type.

## Process
An [original analysis](PyCitySchools.ipynb) was completed with the Pandas Library in Jupyter notebooks. I merged the supplied raw school and student .csv data, inspected and cleansed the data, and sorted, grouped, and summarized the data into dataframes. After the initial analysis was complete, the school board was notified of academic dishonesty for 9th grade reading and math at Thomas High School (THS). I replaced the scores of the dishonest grades at THS and updated the data analysis. The results below compare the original analysis to the [updated analysis](PyCitySchools_Challenge.ipynb) to show the impact of these fradulent grades.

## Results
### How is the district summary affected?
Original District Summary ![Original District Summary](Resources/Images/Original_District_Summary.png)

Updated District Summary ![Updated District Summary](Resources/Images/Updated_District_Summary.png)
Removing the Thomas High School (THS) 9th grade students hardly impacted the district analysis. There were changes to score averages in the tenths of percents. This is not surprising as this subset of data was only 461 of 39170 total students across all schools.
  
### How is the school summary affected?
- Original School Summary ![Original_School_Summary](Images/Original_School_Summary.png)
- Updated School Summary ![Updated_School_Summary](Images/Updated_Top_School_Summary.png).
The school summary shows much more changes in the analysis. There was a slight decrease in the average math score, while the average reading score slightly increased. However, the percentage passing math, reading, and overall passing percentage dropped significantly.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
With the original analysis, Thomas High School was ranked 2nd based on overall % passing metrics. After the second analysis, removing 9th grade reading and math scores, THS dropped in ranking down to (XXXX).

### How does replacing the ninth-grade scores affect the following:
  - #### Math and reading scores by grade
    - Original Math and Reading Scores
    - Updated Math and Reading Scores
    - Analysis
    
  - #### Scores by school spending
    - Original Scores by School Spending
    - Updated Scores by School Spending
    - THS spends $638 per student, and therefore falls in the $631-645 bin of bucket spending.
    
  - #### Scores by school size
    - Original Scores by School Size
    - Updated Scores by School Spending
    - THS with a size of 1,635 students, and therefore falls in the medium bin of school size.
   
  - #### Scores by school type
    - Original Scores by School Type
    - Updated Scores by School Type
    - THS is a charter school.

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
- 1
- 2
- 3
- 4
