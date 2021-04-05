# School_District_Analysis
School District Analysis project for UT Austin Data Analysis Bootcamp

## Project Overview
A School District employee has requested we analyze standardized test scores and school budgets in order to assist the school board with budget decisions. In addition, reading and math grades for Thomas High School ninth graders appear to have been altered, and the employee has asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact, then perform the analysis again with the adjusted data.

## Resources
- Data Sources: schools_complete.csv, students_complete.csv
- Software: Python 3.7.6, Jupyter Notebook

## Results
### How is the district summary affected?
Across the district, the removal of the Thomas High School ninth graders’ scores did not affect the district average reading score significantly, but it did cause the average math score to drop by 0.1 points, from 79.0 to 78.9. This indicates that the  scores for Thomas’ ninth graders averaged higher than the rest of the district.

### How is the school summary affected?
In the school summary, the only school that was affected was Thomas High School. Its average math scores dropped from 83.42 to 83.35. The percentage of students who passed math dropped from 93.3% to 93.2%.

Thomas High School’s reading scores went up from 83.85 to 83.90. However, the percentage of those who passed dropped from 97.3% to 97.0%. This indicates that the average score of ninth graders was lower than for the rest of the school, but greater than 97.3% of them were passing reading. 

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Relative to the other schools, Thomas High School’s performance did not change much. In both cases Thomas ranked second in terms of overall passing percentage. It’s numbers did decline somewhat, from 90.9% to 90.6%, but this was enough to rank second either way.

### How does replacing the ninth-grade scores affect the following:
#### -Math and reading scores by grade
The math and reading scores by grade for each school were unaffected, except of course for the ninth grade at Thomas.
#### -Scores by school spending
The scores by school spending were unaffected.
#### -Scores by school size
The scores by school size were unaffected.
#### -Scores by school type
The scores by school type were unaffected.

## Summary 
After reading and math scores for the ninth graders were dropped, we saw several changes in the school district analysis. First, we saw that the impact of the Thomas ninth graders scores on the district averages as a whole were minimal, only altering the math average by a tenth of a point. Second, we saw that the average math scores at Thomas went down, lowering both the school average and the percentage of those who passed. Third, we saw that the average reading scores at Thomas went up slightly, but the percentage of those who passed went down, indicating that the ninth graders’ scores were left-skewed. Lastly, the removal of the ninth graders’ scores at Thomas did not affect that school’s ranking against other schools in the district. Thomas High School is still the second-ranked school with or without the ninth graders’ scores.
