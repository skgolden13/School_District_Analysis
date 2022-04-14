# School District Analysis

## Project Overview

Evidence of academic dishonesty has been found in the students_complete.csv file for 9<sup>th</sup> graders at Thomas High School. To uphold state-testing standards, the original standardized testing analysis for the school district has been updated to replace math and reading scores for the affected students with NaNs. Images of the pandas data frames from both the original and updated analysis are included for comparison.

The analysis was performed using python 3.7 and the jupyter notebook. The pandas and numpy libraries were used for analysis and calculations.

The term "original analysis" refers to the initial analysis performed while "updated analysis" refers to the analysis performed after excluding the affected scores.

All raw data files can be found [here](https://github.com/skgolden13/School_District_Analysis/tree/main/Resources).<br/>
All data frame images can be found [here](https://github.com/skgolden13/School_District_Analysis/tree/main/Images).<br/>
The jupyter notebook file for the original analysis can be found [here](https://github.com/skgolden13/School_District_Analysis/blob/main/PyCitySchools.ipynb).<br/>
The jupyter notebook file for the updated analysis can be found [here](https://github.com/skgolden13/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb).

## Analysis Results

### District Summary

The district summary was not significantly affected by removing the 9<sup>th</sup> grade Thomas High School scores. The following changes can be seen between the original analysis (Figure 1) and the updated analysis (Figure 2):
  - Average math score dropped 0.1%
  - Percent of students passing math dropped 0.2%
  - Percent of students passing reading dropped 0.3%
  - Percent of students passing both dropped 0.1%

<p align="center">
  <img width="900" alt="District_Summary" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/District_Summary.PNG"><br/>
  Figure 1: Original School District Summary<br/>
  <br/>
  <img width="900" alt="Updated_District_Summary" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Updated_District_Summary.PNG"><br/>
  Figure 2: Updated School District Summary<br/>
</p>

### School Summary

The metrics for Thomas High School saw no change for the average math and reading scores and a roughly 0.3% drop for the percent passing math, reading, and both. The original and updated school summary data frames can be seen below as Figures 3 and 4 respectively.

<p align="center">
  <img width="900" alt="School_Summary" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/School_Summary.PNG"><br/>
  Figure 3: Original School Summary<br/>
  <br/>
  <img width="900" alt="Updated_School_Summary" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Updated_School_Summary.PNG"><br/>
  Figure 4: Updated School Summary<br/>
</p>

### Top Schools Summary

With the minimal decrease in the percent of students passing overall, Thomas High School remained the second highest performing school in the district. The top five schools summary for the original and updated analysis can be seen below as Figures 5 and 6 respectively.

<p align="center">
  <img width="900" alt="Top_Schools" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Top_Schools.PNG"><br/>
  Figure 5: Original Top Five Schools<br/>
  <br/>
  <img width="900" alt="Updated_Top_Schools" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Updated_Top_Schools.PNG"><br/>
  Figure 6: Updated Top Five Schools<br/>
</p>

### Math Scores by Grade

Math scores by grade are unaffected by the updated analysis aside from the value for 9<sup>th</sup> at Thomas High School being replaced by "NaN." The math scores by grade for the original and updated analysis can be seen below as Figures 7 and 8 respectively.

<p align="center">
  <img width="450" alt="Math_Scores" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Math_Scores.PNG"><br/>
  Figure 7: Original Math Scores by Grade<br/>
  <br/>
  <img width="450" alt="Updated_Math_Scores" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Updated_Math_Scores.PNG"><br/>
  Figure 8: Updated Math Scores by Grade<br/>
</p>

### Reading Scores by Grade

Reading scores by grade are unaffected by the updated analysis aside from the value for 9<sup>th</sup> at Thomas High School being replaced by "NaN." The reaading scores by grade for the original and updated analysis can be seen below as Figures 9 and 10 respectively.

<p align="center">
  <img width="450" alt="Reading_Scores" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Reading_Scores.PNG"><br/>
  Figure 9: Original Reading Scores by Grade<br/>
  <br/>
  <img width="450" alt="Updated_Reading_Scores" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Updated_Reading_Scores.PNG"><br/>
  Figure 10: Updated Reading Scores by Grade<br/>
</p>

### School Spending Summary

The school spending summary was not affected by the updated analysis. The school spending summary for the original and updated analysis can be seen below as Figures 11 and 12.

<p align="center">
  <img width="900" alt="Spending_Summary" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Spending_Summary.PNG"><br/>
  Figure 11: Original School Spending Summary<br/>
  <br/>
  <img width="900" alt="Updated_Spending_Summary" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Updated_Spending_Summary.PNG"><br/>
  Figure 12: Updated School Spending Summary<br/>
</p>

### School Size Summary

The school size summary was not affected by the updated analysis. The school size summary for the original and updated analysis can be seen below as Figures 13 and 14.

<p align="center">
  <img width="900" alt="Size_Summary" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Size_Summary.PNG"><br/>
  Figure 13: Original School Size Summary<br/>
  <br/>
  <img width="900" alt="Updated_Size_Summary" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Updated_Size_Summary.PNG"><br/>
  Figure 14: Updated School Size Summary<br/>
</p>

### School Type Summary

The school type summary was not affected by the updated analysis. The school type summary for the original and updated analysis can be seen below as Figures 15 and 16.

<p align="center">
  <img width="900" alt="Type_Summary" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Type_Summary.PNG"><br/>
  Figure 15: Original School Type Summary<br/>
  <br/>
  <img width="900" alt="Updated_Type_Summary" src="https://github.com/skgolden13/School_District_Analysis/blob/main/Images/Updated_Type_Summary.PNG"><br/>
  Figure 16: Updated School Type Summary<br/>
</p>

## Analysis Summary
