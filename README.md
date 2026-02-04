# Power_BI_Exam
 Student Performance Dashboard – Academic & Behavioral Insights
 Project Overview

This project is an interactive Power BI Dashboard designed to analyze and visualize student academic performance, attendance, and behavioral patterns across different classes, subjects, and terms.

The dashboard enables educators and administrators to identify trends, evaluate performance categories, and understand how attendance and behavior impact academic outcomes.

 Objective

To build a comprehensive Power BI dashboard that:

Tracks student performance across subjects and terms

Analyzes attendance patterns

Visualizes behavioral incidents

Provides actionable insights using KPIs, trends, and drill-through analysis

 Duration

2.5 – 3 Hours

 Dataset Description

The project uses four CSV files:

1. Students.csv
Column Name	Description
StudentID	Unique student identifier
Name	Student name
Gender	Gender of student
Class	Class/Grade
Section	Section
2. Scores.csv
Column Name	Description
StudentID	Student identifier
Subject	Subject name
ExamType	Exam type
Score	Marks obtained
MaxScore	Maximum marks
Term	Academic term
3. Attendance.csv
Column Name	Description
StudentID	Student identifier
Date	Attendance date
Status	Present / Absent
Reason	Reason for absence
4. Behavior.csv
Column Name	Description
StudentID	Student identifier
Date	Incident date
BehaviorType	Type of behavior
Notes	Additional remarks
 Data Modeling & Cleaning

All datasets were loaded into Power BI using Power Query

Proper data types assigned to each column

Missing values handled appropriately

A star schema model was created with Students as the central table

Relationships established using StudentID

 DAX Measures Created

Key calculated measures include:

% Score

Average Score per Subject

Attendance %

Behavior Count per Type

Performance Category (High / Medium / Low)

Total Students

Average Attendance

Average Score

 Visualizations Included

Bar Chart – Average scores by Subject and Class

Line Chart – Performance trend by Term

Donut Chart – Distribution of behavior types

Table – Student-wise scores with conditional formatting

Card Visuals – Key KPIs such as total students, average attendance, and average score

 Interactivity Features

Slicers for Class, Section, Subject, and Term

Drill-through page for individual student profiles

Tooltip pages with mini visualizations

Bookmark navigation to switch between Academic and Behavioral views

 Mobile Optimization (Optional)

Mobile layout designed using Power BI Mobile View

Optimized KPI cards and charts for smaller screens

 Deliverables

Student Performance Dashboard.pbix

Optional insights documentation

README file (this document)

 Key Insights (Sample)

Higher attendance percentages correlate with better academic performance

Certain behavior types are more frequent in specific classes

Performance trends vary significantly across academic terms

 Tools & Technologies

Microsoft Power BI Desktop

Power Query

DAX

CSV Data Sources
