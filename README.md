# Student Marks Tracker (MS Excel)

An Excel project that tracks the marks of 100 students and automatically calculates Average, Total and Pass/Fail results.

## Columns
| Column | Description |
|---|---|
| Roll No, Name | Student details |
| Python, Maths, Tamil, AI Basics, English | Subject marks (out of 100) |
| Days Present | Attendance days |
| Average | `=AVERAGE(C2:G2)` |
| Total | `=SUM(C2:G2)` |
| Result | `=IF(MIN(C2:G2)<40,"FAIL","PASS")` |

## Rule
A student fails if the marks in any one subject are below 40.

## Features
- Sample data of 100 students
- Formulas using SUM, AVERAGE, IF and MIN
- Conditional formatting to highlight low marks and failed students

## How to use
1. Download `Student_Marks_Tracker.xlsx`
2. Open it in Microsoft Excel
3. Replace the sample marks with your own data. The formulas update automatically

## Result of sample data
- Total students: 100
- Pass: 82
- Fail: 18

## Author
Pravin Raj S
