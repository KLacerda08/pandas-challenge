DISTRICT HIGH SCHOOL DATA 

District high school data was presented in two .csv files:
* schools_complete.csv, which included data for each high school, including the name, 
	type, number of students (size), and budget.
* students_complete.csv which included data such as standardized math and reading scores per student, 
	high school attened, student name and gender.

DATA EVALUATION
The data was evaluated to provide a district overview, school summaries, and various metrics as follows: 

-District Summary - (dist_summary_df)
  * Total Number of Schools
  * Total Number of Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

-School Summary - (sum_renamed_df)
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

-Top Performing Schools (By % Overall Passing) - (top5_df)
-Bottom Performing Schools (By % Overall Passing) - (bot5_df)
-Math Scores by Grade - (MathByGrade_df)
-Reading Scores by Grade - (ReadByGrade_df)
-Scores by School Spending - (cost_df)
-Scores by School Size - (size_df)
-Scores by School Type - (type_df)

RESULTS DISCUSSION: 

The school district data shows several interesting trends, namely: 
1. Only 65.17 % of students across the district are passing both reading and math (with scores 70% or above). 
2. Based on percent of students passing both reading and math (% Overall Passing):
    - The top 5 (best) performing schools are charter schools.
    - The bottom 5 (worst) schools are district schools.  
3. Within the same school, math scores and reading scores remain relatively consistent across all four grades.
4. The schools with the smallest per student budget have the highest %Overall Passing ratings, while the schools 
	with the highest budget per student have the lowest % Overall Passing ratings.
5. Small and Medium sized schools were relatively consistent in % Overall Passing. 
6. Charter schools consistently outperformed district schols across all measured categories (Average Math Score, 
	Average Reading Score, percent of students passing math (% Passing Math), percent of students passing 
	reading (% Passing Reading), and % Overall Passing. 