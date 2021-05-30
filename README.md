### Project: School_District_Analysis
Working with Jupyter Notebook, Anaconda and Python Pandas to analyze data for a school district
## Overview of the school district analysis
This challenge invovled working with the school district to take a large dataset of high school students and analyzing the student scores within certain grades and schools.  Here are list of required deliverables from the district:
- Provide a snapshot of the district's key metrics presented in table format
- Provide an overview of the key metrics for each school in table format
- List the top five and bottom five performing schools based on the overall passing rate
- Caculate the average math and reading scores by students in each grade level
- List school performance based on budget per student, school size and type of high school.

## Summary of data analysis

By conducting this analysis, the school district can affectively determine their next steps in terms of funding per student capita, per school, and even per grade based on the results provided.  The data shown will allow also coduct a comparison of the student success percentages on reading versus math, the passing percentages and the overall percentages of passing students.  I've also created grouping of student scores by the school spending, the school size and the type of school.

There has also been a suspicion of fraud in editing the student test results.  With the program provided, I have been able to create a table of information, clear the values out and re-replaced those values with the same data set to ensure there is no mishandling errors or any fradulent activity in determining these metrics.  As an example, there was a concerted effort to focus on the results by Thomas High School.  Towards the middle and latter part of the code, it will show that there is no ill-intent, no evidence of fraud or suspicious activity.

In fact, with this program, there is built-in automation to read any comma-delimited (.CSV) dataset with the same formatted columns.  Simply change the name of the file and the analysis can be determined in the same manner.  Different types of datasets can also be read, by tweaking and refactoring the code to gain the same benefits.  

This program was written to automate and calculate the passing percentages of a dataset for this entire school district and, for that matter, can be utilized for many school districts in a very efficient manner.  It will also help in determining the total budgetary amounts per capita, per grade, per school if those metrics are analytics are necessary data points.

With the work conducted by this program the district is able to take a deeper dive into analyzing the ninth-grade scores for Thomas High School, for example.   The case study was to replace their ninth-grade scores which may further provide information on how the other students scores are affected in passing percentages.

As depicted below, we'll first take a look at the Math Versus Reading Scores Per Grade:

Next is the Scores by School Spending:

This dataframe depicts the Scores by School Size:

Lastly, this dataframe shows the Scores by School Size:


Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs