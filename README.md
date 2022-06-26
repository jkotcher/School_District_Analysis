# School_District_Analysis


# Overview of the School District Analysis

## Purpose
The purpose of this analysis was to review data of school performance and create a district summary.  There was found to be academic dishonesty and so we had to go back into the analysis code to remove the data that was affected and replace it with new data.  The academic dishonesty was found to be among ninth graders at Thomas High School.  These students scores were replaced with NA's in the student dataset since they no longer had grades due to the academic dishonesty.

# Results

## District Summary

### Original District Summary

![district_summary](https://user-images.githubusercontent.com/29406929/175829960-842f93de-e5c0-473c-925b-5027c80830fe.png)


### Revised District Summary

![Revised_district_summary](https://user-images.githubusercontent.com/29406929/175830064-0f276a9f-61f6-49c6-8235-c2d3e5df5d2e.png)


## School Summary
1. The school summary is affected because removing the scores for Thomas high school is now based on three grades as oppose to four
2. The spending per student is now looks larger for Thomas high school
3. The percentages are based on three grades and thus they are vastly different


![School_summary](https://user-images.githubusercontent.com/29406929/175830453-9fd35a4e-7ee4-485f-a783-ae004e932e31.png)

In some iterations of the analysis there Thomas High School appeared to have better scores when only the three grades that were not the ninth grade was accounted for.  In other instances due to not getting the right code in place working to do what it was supposed to the scores were worse because they were the old scores.

## Math and Reading scores by grade
1. Removing the math and reading scores for ninth graders at Thomas high school will mean their performance can't be recorded.
2. All other ninth grader information becomes inflated because the one school is taken out for one specific grade

### Math Scores
![Screen Shot 2022-06-26 at 3 34 50 PM](https://user-images.githubusercontent.com/29406929/175830995-12b81a44-2933-4cdf-bc88-718ba3f4fd7b.png)


### Reading Scores
![Screen Shot 2022-06-26 at 3 35 07 PM](https://user-images.githubusercontent.com/29406929/175831014-2efb4ffa-4efb-48f9-b05c-9ea075d2020c.png)


## Scores by spending

![Screen Shot 2022-06-26 at 3 33 22 PM](https://user-images.githubusercontent.com/29406929/175831052-6b6b48e8-3ec1-468f-8618-5593ea44673e.png)


## Scores by size

![Screen Shot 2022-06-26 at 3 40 35 PM](https://user-images.githubusercontent.com/29406929/175831121-f17c189a-9505-4830-848f-6ce6b3813c79.png)


## Scores by type

![Screen Shot 2022-06-26 at 3 35 24 PM](https://user-images.githubusercontent.com/29406929/175831135-0de76e0a-c1f0-4e28-9355-225da178e374.png)


# Summary
1. After changing the scores of the ninth graders at Thomas High School the performance of the school as seen in previous iterations of code has been higher than what it would have been
2. Scores by grade are now different because the number of students has been changed both in the district analysis and the school summary.
3. Thomas High schools' spending per student looks larger than it actually is because the ninth graders were no longer counted as having grades.
4. This changes the school boards' view on how to allocate funds to Charter schools.  If this happened at one charter school could it at others and then means expenses for various other things to make sure this doesn't happen again.



