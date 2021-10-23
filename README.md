### School_District_Analysis

## Overview
The school board had notified Maria that there seems to be academic dishonesty at the math and reading levels for Thomas High School ninth grade.  In order to analyze the impact of the potential dishonesty it was asked that the overall school data be changed to include all NaN's for math and reading for Thomas High School 9th graders. In order to make the changes the following was done to the initial data. 
1. Loc method was used to select all math and reading scores from the ninth grade. 
2. Comparison operator was used to retrieve all rows with "Thomas High School" in the school_name column. 
3. Comparison operator was used to retrive all rows with the "9th grade" in the grade column.
4. Logical and comparison operators are used to retrieve all the rows that for reading_score, math_score for Thomas High School 9th graders
5. Finally the reading and math scores are replaced by NaN's - in order that they will no longer be considered in calcuation of the school district summary
![image](https://user-images.githubusercontent.com/90973718/138523449-0a647aa0-0671-4749-b00d-2dc6c5997516.png)


## Results
Replacing the 9th grade scores with NaN's for Thomas High School trully did not impact the overall results.  The total number of 9th grade students is 461.  The total number of students at Thomas High School from 10th -12 is 38,709.  The 461 9th graders only represent 1% of the student population.  Making any changes to the maht and reading scores by grade, scores by school spending, scores by school size and scores by school type trivial. 

  ### District Summary
The change in 9th grade reading and math scores did not greatly impact the overall results of the district_summary, and did not impact at all if considering rounding. 
Initial Analysis
![image](https://user-images.githubusercontent.com/90973718/138523625-f2fda21b-06bd-4f3d-815c-14f0af8dcb88.png)

Revised Analysis
![image](https://user-images.githubusercontent.com/90973718/138524080-287d727b-a773-4054-bd6f-600513fd02f7.png)

## School Summary
### *Scores by School Spending*
When reveiwing the spending by school compared to the math and reading scores shows that there is not a correlation between a higher budget and better performing students.  In fact the schools that spent the least amount on their students had the highest overall passing percentage of 90% compared to the next spending range at 81%

![image](https://user-images.githubusercontent.com/90973718/138525302-c8823179-2eb9-47cd-a140-f50ed16c9d9e.png)

### *Scores by School Size*
The report also dives into the any correlation between reading and math scores compared to the overall size of the school. At this level we are able to see that the overall school size does seem to correlate to the overall passing of reading and math.  The small and medium size schools are close at 90% and 91% respectively.  Whereas the schools that are  large (2,000 - 5,000 students) the overall passing of reading and math significantly drops to 58%.
![image](https://user-images.githubusercontent.com/90973718/138537228-280126a3-c614-4f72-a7dc-7e7e258a35d9.png)

### *Scores by type of School*
Lastly the report dives into on strong the connection between the typ of school (charter vs district) plays in the overall success of reading and math.   From the chart below you can see that it plays a significant role.  Charter schools have a 90% overall passing percentage of math and reading where District schools are only at 54%.
![image](https://user-images.githubusercontent.com/90973718/138537419-36af23a2-e582-447b-8fa3-aca7aefeb9c6.png)


# Summary
In summary the changes made to the Thomas High School 9th graders math and raeding scores (change to NaN's) had an insigificant impact to the overall school analysis. The calculated averages for math and reading and the percentages passing of math and reading and overall passing percentage for Thomas High School changed less than a percent due to removing the 9th grade results  It is in my opinion that the school board continue with the budgeting process based on the updated data.    
  
