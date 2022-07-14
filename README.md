# School_District_Analysis

## Analysis
The purpose of this analysis is to see the impact of removing Thomas High School 9th graders' math and reading scores from the dataset, while reporting on whether this change was significant to the rest of the dataset. 

## District Summary Impact
After reviewing the data, it does not appear that there is any significant change.

## School Summary Impact
<img src="https://github.com/Ampickett/School_District_Analysis/blob/main/Images/SchoolSummary.png?raw=true" width="700" height='700'>
When looking at the school summary report, Thomas High School was reporting with an overall passing score of 91 percent. After removing the 9th graders' math and reading scores, we see that Thomas High School drops down with an overall passing rate of 65%.

## Replacement of scores Impact on Thomas High School
By replacing the scores with NaN, we do not see any impact on Thomas High Schools when it comes to math or reading scores. Since we are only reporting NaN for Thomas High School 9th graders, the other schools and grade levels were also not impacted.
  * Impact on Math and Reading scores by grade: We do not see any impact with replacing with NaN.
  * Impact on Scores by school spending: We do not see any impact with spending on reading or math scores. 
  * Impact on Scores by school size: We do not see any change in average math or reading scores. However, we do see a change with passing percentages of medium sized schools but it is very small. 
  
<img src="https://github.com/Ampickett/School_District_Analysis/blob/main/Images/SchoolTypes.png?raw=true"  width="700" height='300'> 
  
  * Impact on Scores by school type: We do not see any changes on math or reading scores between charters and districts. Removing the 9th graders' scores does show a reduction in charter schools passing percentages. This change is very small and does not impact the bigger picture by much. 

## Summary
Although we are replacing around 400+ 9th grade students scores from our dataset, it does not impact the bigger picture by much. We see less than a 0.1 percent decrease overall. The biggest impact is that overall percentage of Thomas High School dropped from being a top 5 school, to near the bottom of the rankings. If we were to report on these 9th graders with accurate data, it might change the entire analysis completely. 
  










