# Student Marks Tracker

A dataset of 100 students' marks with Average, Total and Pass/Fail results, built for practicing Excel formulas and data analysis.

## Data File
`Student_Data_1.csv` has one row per student.

| Column | Description |
|---|---|
| Roll No, Name | Student details |
| Python, Maths, TAMIL, AI Basics, English | Subject marks (out of 100) |
| Days Present | Attendance days |
| AVERAGE | Average of the 5 subject marks |
| TOTAL | Sum of the 5 subject marks |
| RESULT | PASS or FAIL |

## Rule
A student fails if the marks in any one subject are below 40.

## Excel Formulas Used
Open the CSV in Excel. If you want the columns to calculate automatically, use these formulas in row 2 and fill down:

| Column | Formula |
|---|---|
| Average | `=AVERAGE(C2:G2)` |
| Total | `=SUM(C2:G2)` |
| Result | `=IF(MIN(C2:G2)<40,"FAIL","PASS")` |

You can also add conditional formatting to highlight marks below 40 and FAIL rows.

## Result of the Data
- Total students: 100
- Pass: 82
- Fail: 18

## How to Use
1. Download `Student_Data_1.csv`
2. Open it in Microsoft Excel or Google Sheets
3. Replace the sample marks with your own data and apply the formulas above

## Author
**Pravin Raj S**
GitHub: [spravinraj78-cpu](https://github.com/spravinraj78-cpu)
