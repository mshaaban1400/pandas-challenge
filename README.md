# pandas-challenge
In this exercise, we were given a set of instructions to analyze data from the district-wide standardized test results in the capacity of the new Chief Data Scientist for my city's school district. We created a report including the following data:

# District Summary
* Total number of unique schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

# School Summary
* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

# Highest Performing Schools (by '% Overall Passing')
Sort the schools by "% Overall Passing" in descending order and display the top 5 rows and the results in a DataFrame called "top_schools".

# Lowest-Performing Schools (by '% Overall Passing')
Sort the schools by "% Overall Passing" in ascending order and display the top 5 rows and save the results in a DataFrame called "bottom_schools".

# Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

# Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

# Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student) with the following bins as cutoffs: "<$585", "$585-630", "$630-645", "$645-680". Then calculate mean scores per spending range and use the scores to create a DataFrame called "spending_summary" including the following metrics:
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

# Scores by School Size
Create a table that breaks down school performance based on average school size with the following bins as cutoffs: "Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)". Then calculate mean scores per size range and use the scores to create a DataFrame called "size_summary" including the following metrics:
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

# Scores by School Type
Use the "per_school_summary" data frame to create a new data frame called "type_summary" which should show school performance based on the "School Type".