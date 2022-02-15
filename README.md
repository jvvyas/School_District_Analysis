# School_District_Analysis

## Software Used: Python 3.10, Anaconda, Jupyter Notebook, GitHub 2.27
**Output Files**: Py_City_Schools.ipynb & PyCitySchools_Challenge.ipynb (with NaN)
Results / Analysis


## Analysis Task
Repo consists of two technical analysis deliverables and a written report of a
school board request of students_complete.csv/school_complete.csv files.

## Overview of Project
The school board has notified Maria and her supervisor that the
students_complete.csv file shows evidence of academic dishonesty; specifically,
reading and math grades for Thomas High School ninth graders appear to have
been altered. Although the school board does not know the full extent of the
academic dishonesty, they want to uphold state-testing standards and have
turned to Maria for help.

## Summary
Maria has asked you to replace the math and reading scores for Thomas High
School with NaNs while keeping the rest of the data intact. Once you’ve replaced
the math and reading scores, Maria would like you to repeat the school district
analysis that you did in this module and write up a report to describe how these
changes affected the overall analysis.

In this comparative analysis between counting and not counting Thomas High
School Ninth Grade scores to see average and scores at:

- District Level
- School Type Level
- School Level

## Resources
Data Sources: students_complete.csv/school_complete.csv files
Client Requirements from School Board



**How is the district summary affected?**

- Average Math Scores: moved from 79 to 78.9 as a result of taking out Thomas
High School Ninth Grade scores.
- Average Reading Scores did not change.
- Percent Passing Math moved from 75% to 74%.
- Percent Passing Reading moved from 86% to 85%.
- Percent Overall Passing moved from 65% to 64%.



**How is the school summary affected?**

- Average Math at Thomas decreased from 83.42 to 83.35.
- Average Reading at Thomas slightly increased from 83.84 to 83.89.
- Average Percent Passing Math at Thomas greatly decreased from 93.3% to
66.9%.
- Percent Passing Reading at Thomas decreases from 97.3% to 69.7%.
- Average Percent Overall passing both Math and Reading decreased from 90.9%
to 65.1%.


**How does replacing the ninth graders’ math and reading scores affect Thomas
High School’s performance relative to the other schools?**

Thomas High is no longer in the top 10 after adjusting 9th grades scores with
NaNs.


**How does replacing the ninth-grade scores affect the following:**

- Math and reading scores by grade
- Thomas High School&#39;s math scores were removed from the 9th grade and all
other scores remained the same.
- Scores by school spending
- With the removal of the 9th grade scores, the overall passing percentage
decreased from 62.9% to 56.4%.
- Scores by school size
- Thomas High School is a medium sized school and no real findings after adding
the NaNs.
- Scores by school type
- For the Charter, therefore, the changes were as follows:
- Average Math scores declined from 83.47 to 83.46.
- Average Reading scores were slightly higher: 83.89 compared to 83.9.
- Percent Passing Math declined from 93.6 to 90.3.
- Percent Passing Reading declined from 96.6% to 93.1%.
- Percent Overall Passing decreased from 90.4% to 87.2%.

This analysis more than likely concludes that there is some sort of academic dishonesty because of narrowing
down on the school itself relative to other schools.
