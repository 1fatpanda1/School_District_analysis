# School_District_analysis

## Overview
We are using pandas to help Maria import, clean, and organize the local standardized test data in an easy to view format. We are also simulating a situation where the 9th graders from a certain school did not have data which might change the results of that school’s data

## Results

Replacing the 9th grade class results changed the data for Thomas High School in the following ways
•	The district summary is relatively unchanged 
•	The school summary is unchanged except for Thomas High
•	Thomas High school’s average math score and % passing math. Their average reading score, % passing reading and overall percent passing decreased. 
•	Despite the average scores and percentage passing decreasing, Thomas High remained the 2nd best performing school
before
![top5before.png](https://github.com/1fatpanda1/School_District_analysis/blob/main/Resources/Top%205%20before.png)
after
![top5after.png](https://github.com/1fatpanda1/School_District_analysis/blob/main/Resources/Top%205%20after.png)

•	Math and reading scores by grade only affected the 9th grade

•	Scores by school spending decreased a little but not enough to impact the charts when rounded to the nearest % or .1 score
before
![spendbefore](https://github.com/1fatpanda1/School_District_analysis/blob/main/Resources/Spending%20ranges%20before.png)
after
![spendafter.png](https://github.com/1fatpanda1/School_District_analysis/blob/main/Resources/Spending%20ranges%20after.png)

•	Scores for Medium schools decreased a little but not enough to impact the chart when rounded to the nearest % or .1 score
before
![bysizebefore](https://github.com/1fatpanda1/School_District_analysis/blob/main/Resources/By%20school%20size%20before.png)
after
![bysizeafter.png](https://github.com/1fatpanda1/School_District_analysis/blob/main/Resources/By%20school%20size%20before.png)

•	Scores for charter schools decreased a little but not enough to impact the chart when rounded to the nearest % or .1 score


## Summary
Overall replacing the school data mostly affect Thomas High’s individual metric the most. Before formatting the tables to round to nearest percentage and .1 math score, it is clear that the average school and % passing decrease along the board for Charter schools, Medium sized schools, and spending range per student. The most heavily impacted metric which we did not calculate would have been average scores and percentages amongst ninth grade students.
