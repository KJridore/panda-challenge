# panda-challenge
In the conducted analysis, a multi-faceted examination of school district data was performed to evaluate and summarize the performance of schools and students across various metrics. Below is a detailed summary of the work done:

District Summary
Data Preparation: Utilized necessary codes to perform calculations and create a snapshot of the district's key metrics encapsulated in a DataFrame.
Key Metrics Calculated:
Total number of unique schools.
Total number of students.
Total budget.
Average math score.
Average reading score.
Percentage of students passing math.
Percentage of students passing reading.
Percentage of students passing both math and reading.
District Summary DataFrame: Created a new DataFrame called district_summary which houses the above calculations, facilitating a comprehensive view of the district's performance.
School Summary
School-specific Metrics: Utilized various codes to calculate key metrics for each school, including:
School name and type.
Total students and budget (including per student budget).
Average scores and passing percentages in math and reading.
Per School Summary DataFrame: Formulated a per_school_summary DataFrame to store and present the calculated data, offering a school-wise breakdown of the performance metrics.
Performance Analysis based on % Overall Passing
Highest-Performing Schools:
Sorted schools based on the percentage of overall passing in descending order.
Saved the top 5 in a DataFrame named top_schools.
Lowest-Performing Schools:
Conversely, sorted schools by ascending order of overall passing percentage.
Documented the bottom 5 in a DataFrame named bottom_schools.
Grade-wise Analysis
Math Scores by Grade:
Calculated average math scores for each grade (from 9th to 12th) at each school.
Combined this data into a singular DataFrame named math_scores_by_grade.
Reading Scores by Grade:
Parallelly, derived the average reading scores for each grade level at each school.
Compiled the data in a separate DataFrame called reading_scores_by_grade.
Analysis Based on School Spending
School Spending Analysis:
Binned data based on per student spending ranges using the pd.cut function.
Calculated mean scores and passing percentages per spending range.
Integrated this data into a spending_summary DataFrame.
Analysis Based on School Size
School Size Analysis:
Utilized pd.cut to categorize schools based on the size of the student population.
Consolidated the findings into a size_summary DataFrame, providing insights into performance metrics based on school size.
Analysis Based on School Type
School Type Analysis:
Grouped the per_school_summary DataFrame based on the 'School Type' and averaged the results to glean insights into performance trends by school type.
Created a type_summary DataFrame to encapsulate this data.
Written Report
Summary of Analysis: Presented a cohesive written analysis summarizing the entire process and findings.
Conclusions and Comparisons: Drew two substantial conclusions from the data analysis, providing an in-depth comparison of the calculations performed.
This exhaustive analysis serves as a robust tool to gauge the performance of schools in the district across multiple parameters, aiding in informed decision-making and planning for the educational authorities.
