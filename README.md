# School_District_Analysis

## Challenge Overview
A City School District has given me the task of analyzing High School funding and High School Student standardized testing scores in order to provide insight on performance trends and patterns. The challenge for this module required the following tasks:

1. Replace the ninth-grade math and reading scores from Thomas High School with Nan.
2. Create DataFrames for the following:
    - District Summary
    - School Summary
      - High and Low performing schools analysis
    - Scores by DataFrames:
      - Grade
      - Spending
      - School Size
      - School Type
3. Lastly the following questions were to be answered in regards to the analysis:
     - How does replacing the ninth-grade scores affect each DataFrame's analysis.

## Resources
Data Sources: schools_complete.csv, students_complete.csv
Software: Python 3.7.6, conda 4.8.3, Visual Studio Code 1.46.0, Jupyter Notebook 6.0.3

## Summary Q/A
1. How is the district summary affected?
    - When looking across both district summaries, there is not a significant change between test scores or passing percentages. This would be expected since only a small sample of the entire data set was changed.
2. How is the school summary affected?
    - The Thomas High School score averages and percentages dropped significantly due to the lack of scores for the ninth grade students.
3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
    - Thomas High School was ranked as the 2nd highest school when analyzing rank based on Overall Passing Percentage. However, with the updated 9th grade scores, the school dropped its rank significantly to the 8th highest.
4. How does replacing the ninth-grade scores affect the following?
    - Math and Reading Scores by Grade
      - nan is presented under 9th Grade math and reading scores for Thomas High School.
    - Scores by School Spending
      - The Passing Percentage for the $630-$644 spending range decreased significantly due to the lack of scores for Thomas High School 9th graders.
    - Scores by School Size
      - The Passing Percentage for Medium(1000-2000) Range school size decreased by 6% due to the lack of scores for Thomas High School 9th graders.
    - Scores by School Type
      - The Passing Percentages for Charter Schools decreased by 3-4% due to the lack of scores for Thomas High School 9th graders.
