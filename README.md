# Project Background

McDaniel College, a private liberal arts college founded in 1867, is focused on delivering a top-notch, student-centered education through its undergrad, grad, and certificate programs. The Graduate and Professional Studies division helps fuel McDaniel’s growth by attracting students looking to advance in fields like education, business, and healthcare. To keep a competitive edge and improve student experience, McDaniel values student feedback on courses, instructors, and program structure. As a volunteer data analyst, I’m supporting my professor by analyzing this feedback, identifying trends, and highlighting areas for improvement. My work will inform insights that my professor can present to the Dean to drive data-backed improvements in the graduate programs.

Insights and recommendations are provided on the following key areas: 
- Enrollments trends
- Instructor effectiveness
- Course content and structure
- Student learning experience
- Course duration impact

The R code used for data cleaning, analysis, and visualization of course-related information is available here. 

A PDF copy of the interactive visualizations can also be found here. However, the actual dataset and output files are not publicly shared due to the sensitive nature of student feedback on instructors and courses.

# Data Structure & Initial Checks

image

### Notes:
-	Questions 13 to 35: Rate on a scale of 1 (Strongly Disagree) to 5 (Strongly Agree)
-	The questions are categorised into 3 for better visualization

# Executive Summary

### Overview of findings

In summer 2024, the overall average rating across all course-related questions was above 4, indicating general student satisfaction with course content. However, Question 33, which addresses faculty-student interaction, had the lowest average score at 4.13, highlighting potential for improvement in engagement. Additionally, Program 118 consistently received low scores (below 4) across all categories, and certain instructors, particularly P57 in Program 116, received ratings below 3 on effectiveness-related questions, signalling specific areas that warrant attention.

# Insights Deep Dive

### Enrollments trends
•	Program 104 leads with the highest enrollment (192 students), while programs like 111, 113, 114, and 119 have fewer than 10 students.
•	Fewer than 50 students enrolled in most programs except for 101, 103, 104, 107, 108, and 109.
•	Most students (100%) agreed they could preview the course structure a week before the start date, with exceptions in programs 101, 103, 104, 107, 108, 111, and 118.

![Total enrollments](images/plot1.png)

![Course preview](images/plot2.png)







