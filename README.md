# School_District_Analysis

## Overview of the school district analysis:
In this analysis we are assisting Maria, a Chief Data Scientitst of a city school distric, she is responsible for preparing all standarized test data for analysis, reporting and presentation to provide insight about performance trends and patterns. We analysed data on student funding and student's standarized test scores by aggregating data and show casing trends in school performaces. 

The school board notifies Maria that one of the files (students_complete.csv) shows evidence of academic dishonesty for reading and math grades in Thomas High School ninth graders and they appear to have been altered. 

We will modifying the math and reading scores for Thomas High School for the ninth graders to show NaNs and once we replace this datat we will repeat the school district analysis. This analysis will assist the school board and superintendent make the decisions regarding the school budgets and priorities.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

- How is the district summary affected?
  - The district summary was affected very slightly to the following: "Average Math Score" by 0.1%, "% Passing Math" by 0.2% , "% Passing Reading" by 0.3% , and "% Passing Overall" by 0.1%. Determined below: 
  
#### PyCitySchool Challenge
![Distric Summary After](https://github.com/Lesliec87/School_District_Analysis/blob/main/Resources/PycitySchool%20Challenge.png)

#### PyCitySchool
![Distric Summary Before](https://github.com/Lesliec87/School_District_Analysis/blob/main/Resources/PycitySchool.png)

- How is the school summary affected?
  - Also the school summary was very slighty affected with only changes to Thomas High School by 0.1% to 0.3% as you can determine below: 
 
 #### PyCitySchool Challenge
 ![School Summary After](https://github.com/Lesliec87/School_District_Analysis/blob/main/Resources/PycitySchool%20challenge%20per%20school.png)
 
 #### PyCitySchool
 ![School Summary After](https://github.com/Lesliec87/School_District_Analysis/blob/main/Resources/PycitySchool%20per%20school.png)
 
- How does replacing the ninth graders??? math and reading scores affect Thomas High School???s performance relative to the other schools?
  - It did not affect Thomas High School's performance since they are still placed in the same place compared to other schools and were ultimately in still in the top schools. 

#### PyCitySchool Challenge
![School Summary After](https://github.com/Lesliec87/School_District_Analysis/blob/main/Resources/Top%20Schools%20PycitySchool%20Challenge.png)

- How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade
   - Same slight change by 0.1% to 0.3%
  - Scores by school spending
   - No change 
  - Scores by school size
   - No change 
  - Scores by school type
   - No change


## Summary: 

After removing and calculating without 9th graders for Thomas High School the changes we determined were the following: 
- District Summary was affected 
- School summary was affected 
- Math and Reading average scores 
- Overall passing scores were affected 

In conclusion Thomas High School has still good performance overall for most of the grades so we can confirm that the discrepancy for the 9th graders scores does not affect the schools overall scores and the decisions of the schools budgets and priorities will not have major consecuences. 
