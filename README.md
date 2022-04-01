# School_District_Analysis
# Overview
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysi

# Purpose
 Replace ninth-grade reading and math scores
 Repeat the school district analysis
 
 # Summary
Using the Pandas loc method with conditional statements and comparison and logical operators, I selected the ninth-grade reading and math scores for Thomas High School. Then, used the Pandas NumPy module to change the reading and math scores to NaN.

 The loc method is used to select all the reading and math scores from the ninth grade at Thomas High School. Inside the loc method, the following are completed:

A comparison operator is used to retrieve all the rows with Thomas High School in the "school_name" column of the student_data_df
A comparison operator is used to retrieve all the rows with the ninth grade in the "grade" column of the student_data_df.
Logical and comparison operators are used to retrieve all the rows with the "reading_score" column for Thomas High School ninth graders from the student_data_df.
Logical and comparison operators are used to retrieve all the rows with the "math_score" column for Thomas High School ninth graders from the student_data_df.
The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs.





