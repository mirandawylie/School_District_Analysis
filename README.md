# School District Analysis

## Overview
Annual school district analysis was compromised due to academic dishonesty of Thomas High School ninth graders. To uphold the state-testing standards, the school district data has been reconfigured to remove the math and reading scores for Thomas High School ninth graders. With these compromised results removed, the annual district analysis was able to determine the following:

* District summary
* School summary
* Top 5 and bottom 5 performing schools, based on the overall passing rate
* Average math score for each grade level from each school
* Average reading score for each grade level from each school
* Scores by school spending per student, by school size, and by school type

Sources: Python 3.7.9, Conda envs PythonData

Link to school district data: https://github.com/mirandawylie/school_district_analysis/tree/main/resources

## Results
* District summary
![district_summary.png](Module4_Pandas/school_district_analysis/images/district_summary.png)
* School summary
![school_summary.png](Module4_Pandas/school_district_analysis/images/school_summary.png)
* Top 5 performing schools, based on the overall passing rate
![top_five_schools.png](Module4_Pandas/school_district_analysis/images/top_five_schools.png)
* Bottom 5 performing schools, based on the overall passing rate
![bottom_five_schools.png](Module4_Pandas/school_district_analysis/images/bottom_five_schools.png)
* Average math score for each grade level from each school
![math_scores_by_grade.png](Module4_Pandas/school_district_analysis/images/math_scores_by_grade.png)
* Average reading score for each grade level from each school
![reading_scores_by_grade](Module4_Pandas/school_district_analysis/images/reading_scores_by_grade.png)
* Scores by school spending per student, by school size
![scores_by_school_size.png](Module4_Pandas/school_district_analysis/images/scores_by_school_size.png)
* Scores by school spending per student by school type
![scores_by_school_type.png](Module4_Pandas/school_district_analysis/images/scores_by_school_type.png)

 When comparing the comprised data with the refactored one, following are highlights and questions answered:
* The district summary % overall passing went from 65.17% to 64.9%
* The school summary stays the same except for the results of Thomas High School. 
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - Even with the refactored results, Thomas High School still ranks second, however the overal passing percentage changed from 90.94% to 90.63%
    ![Thomas_HS_scores.png](Module4_Pandas/school_district_analysis/images/Thomas_HS_scores.png)
    ![Thomas_HS_scores_refactored.png](Module4_Pandas/school_district_analysis/images/Thomas_HS_scores_refactored.png)
* How does replacing the ninth-grade scores affect the math and reading scores by grade
    - The math and reading scores by grade stays the same except one will notice “nan” listed for Thomas 8th grade scores.
    ![math_scores.png](Module4_Pandas/school_district_analysis/images/math_scores.png)
    ![match_scores_refactored.png](/Users/randypants/Desktop/Data/Module4_Pandas/school_district_analysis/images/math_scores_refactored.png)
* How does replacing the ninth-grade scores the following:
    - scores by school spending - not affected
    - scores by school size - not affected
    - scores by school type - not affected

## Summary
After the Thomas High School eight grade reading and math scores were replaced the % overall passing in the district summary decreased. The school summary stayed the same except for the results of Thomas High School which had changes to the % passing math, % passing reading and % overall passing. The top and bottom school rankings stayed the same, however the ranking of Thomas High School slightly decreased. The scores by school spending, school size, and school type remained the same.




