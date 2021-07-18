# PyCitySchools
## Purpose
To analyse the results of test scores for reading and math across a school board. The analysis has been groped by spending per student, school size and school type. This analysis is intended to provide insight to how test results vary by grade and by circumstance at the school (budget, size, and school type). 
A secondary analysis was performed after there was cause for concern that the data from grade 9 student at Thomas High School showed evidence of academic dishonesty. Both analyses have been detailed below with discussion surrounding how the analysis changes with the removal of this data. 
## Results
* How is the district summary affected?- Steps 1-4
Below in the original district summary you can see some minor changes where every score has dropped. It does appear that the average reading score has remained the same, it has also dropped- but with rounding it appears identical. The unrounded original number is 81.87784018381414 and the updated number with the requested removal is 81.85579580976001. These changes can tell us how much that data set was influencing our results. The grade 9 students make up (461/39,170) 1.18% of the population size, but are accounting, in the most drastic change account for a -.35% decrease in the grades for  the % passing reading.
Original District Summary
![District Summary OLD](https://user-images.githubusercontent.com/85718354/126074525-2ec16520-51ba-4beb-8f92-0f61c19112f1.JPG)
Adjusted District Summary
![District Summary NEW](https://user-images.githubusercontent.com/85718354/126074453-a50425cc-c93f-4af0-bbd7-8e0acb2aeb17.JPG)
* How is the school summary affected? Steps 5-14
In the original analysis you can see below that Thomas High School had an average math score of 83.41, and average reading score 83.84 a passing math % of 93.27 a padding reading score of 97.31  an overall passing rate of 90.94%
![School Summary OLD](https://user-images.githubusercontent.com/85718354/126075087-68f1b0ac-4303-453a-ab51-5a0280aa485e.JPG)
However, in the new analysis with the grade 9 scores removed- all other schools remain the same as we only removed grade 9 from Thomas High School. 
Average math drops slightly to 83.35 and average reading changes to 83.89 while the passing rates drop for math to 93.18 passing reading to 97.01 and overall passing to 90.63%.
This shows that with the removal of the grade 9 scores the school’s overall rates dropped, but that the school is still high performing across the other grades.
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Relative to other schools in the original analysis Thomas was listed 2nd overall with an overall passing rate of 90.94%. When the analysis is redone removing the grade 9 students their overall passing rate drops to 90.63% keeping them 2nd overall. There is a distinct gap in between charter schools and district schools, charter schools have an overall passing rate above 89% (when you exclude Thomas High School) and district schools are typically within 50%-54%. Replacing the grade nines does decrease their overall rates, however it keeps them in the same location relative to the other schools in the board.

How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade.
Replacing the math and reading scores by grades puts a nan value within the tables as shown below. This is because we didn’t 0 out the grades, as that would have negatively impacted our analysis by taking those 0’s and including them in the averages above bringing them inaccurately down. But using a nan value these amounts are skipped in calculations.
![math scores by grade](https://user-images.githubusercontent.com/85718354/126075573-08a247bb-b5d8-4700-b998-5c3af86fbfa3.JPG)
![reading scores by grade](https://user-images.githubusercontent.com/85718354/126075574-25874cda-9e31-402e-adc1-565839fdb0c7.JPG)
* Scores by school spending
In the tables below you can see the there is no change in the passing rates from the removal of the grade 9 students, there would be slight changes in this list at the decimal place, however from a high-level review that is not significant. This list shows a trend, in that passing scores are higher in schools with lesser budgets per student.
![scores by spending OLD](https://user-images.githubusercontent.com/85718354/126075644-7451f158-c48a-47d1-932c-fed11aa78181.JPG)

![scores by spending NEW](https://user-images.githubusercontent.com/85718354/126076397-ac0e730b-a061-4756-8d4d-012ca3e71157.JPG)

* Scores by school size
With the removal of the grade 9 students at Thomas High School, there is no high-level changes to the overall review of the scores by school size. We can see a large change in overall passing, where small and medium sized schools do significantly better than large schools in terms of overall passing. 
![Size Summary New](https://user-images.githubusercontent.com/85718354/126076475-daf753c5-68e8-4b4e-b1a0-798a8aa56ade.JPG)
![size summary old](https://user-images.githubusercontent.com/85718354/126075786-379f1a6b-ebeb-499b-8ab9-5397f0f089a9.JPG)

* Scores by school type
In this analysis, old and new, we see that charter schools perform better than district schools. The removal of Thomas High School grade 9 students makes no impact to this. 
![type new](https://user-images.githubusercontent.com/85718354/126076562-2792fbc0-2aa3-47b8-8ebd-0923b794bf72.JPG)

![type old](https://user-images.githubusercontent.com/85718354/126075892-61f5e6d9-b93e-4452-8ed4-a422429c919d.JPG)

It logically makes sense that the removal of Thomas High School Grade 9’s have such a limited impact on the overall reviews of budget, size and type of school. That grade 9 class accounts for 1.18% of the dataset, meaning its removal makes sense to not have a drastic impact on the macro analysis.
## Summary of changes from removing reading and math scores for the ninth grade at Thomas High School
1. Thomas High School Average math scores dropped from 83.42 to 83.35
2. Thomas High School average reading scores dropped from 83.83 to 83.72
3.Thomas High School passing math % dropped 93.27% to 93.18%
4.Thomas High School overall passing rate dropped 90.94% to 90.64%

