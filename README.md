# School_District_Analysis
The point of this analysis is to help give insights to someone that works for a school district, named Maria. Some of the grades here will be replaced with NaN's (Not a Number) and keeping the rest as is. In grades 9 to 12. The analysis will show what the test results from are from all of the schools in this district when Thomas High School's 9th to 12th grade student scores are removed from math and reading subjects.

# Deliverable 1:
The loc method was used to select all of the reading and math scores from the 9th grade at Thomas High School. Within the loc method logical operators and comparisons were used to attain data from the reading_score and math_score columns, and were replaced with nan. As seen below

 - ![Thomas_High](https://github.com/GaryGibbs-777/School_District_Analysis/blob/main/Recources/Thomas_High_NAN.PNG)

Deliverable 2:
After subtracting the total student count by the number of 9th graders at Thomas High School from the total number of students in the district, then recalculating the passing math and reading percentages and overall passing percentages. As seen below.
- ![District](https://github.com/GaryGibbs-777/School_District_Analysis/blob/main/Recources/District_Summary.PNG)

- ![District2](https://github.com/GaryGibbs-777/School_District_Analysis/blob/main/Recources/District_Summary2.PNG)

# The School Summary
Using the same techniques used earlier, I made a DataFrame, that includes percentages of how well all the students did in the district, the school budgets, the average math, and reading, and more.
 - ![Total_students](https://github.com/GaryGibbs-777/School_District_Analysis/blob/main/Recources/total_school_percentages.PNG)


# The top 5 and the top 5 worst performing school
I found the top five schools and the top 5 worst schools and the results below in the photo, but to summarise, the total number of students in 10th to 12th grade is 1,174 and of those that passed is 1,094, and those that passed their math class is 1,139
- ![top5](https://github.com/GaryGibbs-777/School_District_Analysis/blob/main/Recources/numbers.PNG)

Next, I did some calculations to find out what percentage of students passed their math and reading classes as seen below:
- ![more_percentage](https://github.com/GaryGibbs-777/School_District_Analysis/blob/main/Recources/more_percentage.PNG)

Next I added the nan to the scores of Thomas High School, using the loc method as seen below:
- ![percents1](https://github.com/GaryGibbs-777/School_District_Analysis/blob/main/Recources/AVG_scores1.PNG)
- ![percents2](https://github.com/GaryGibbs-777/School_District_Analysis/blob/main/Recources/AVG_scores2.PNG) 

I was able to get the average math and reading scores for grades 9 to 12 and pictures of that are below:
- ![percent_last](https://github.com/GaryGibbs-777/School_District_Analysis/blob/main/Recources/AVG_last.PNG)

# Summary

Overall, after relplacing all of the Thomas High School students that are from the 9th grade onward, in reading and math subjects, with a NaN, has made the data go down negatively. And Thomas High got knocked down from 2nd from the top 3 to the near bottom end of the top 10.
