## Ladies_in_Tech_Africa_Salary_Compensation-Excel-Project



## Project Preview

This project provides a comprehensive analysis of employee salaries, department-wise salary distribution, grade level-wise salary distribution, and top 10 highest-paid employees. The project aims to provide insights into salary compensation trends and support informed decision-making.


## Overview

This repository contains data analysis and visualization for the Ladies in Tech Africa salary compensation project.


## Tools Used

* Microsoft Excel for data analysis and visualization
* Excel formulas for dynamic salary calculation and text extraction
* PivotTables for data summarization and analysis
* Bar charts and other visualization tools for data representation


## Repository Structure

* `Data/`: Contains employee data, department-grade level salary ranges, asset schedules, and salary compensation schedules.
* `Pivot_Tables/`: Contains PivotTable designs for employee salary analysis, department-wise salary distribution, grade level-wise salary distribution, top 10 highest-paid employees, and department-wise average salary by grade level.
* `Reports/`: Contains salary compensation reports and asset schedule reports.
* `Documentation/`: Contains project documentation, data dictionary, and other relevant documents.
* `Images/`: Contains screenshots and images used in the project.


## Data Sources

* Employee data: `Data/Employee_Data.xlsx`
* Department-grade level salary ranges: `Data/Department_Grade_Level_Salary_Ranges.xlsx`
* Asset schedules: `Data/Asset_Schedules.xlsx`
* Salary compensation schedules: `Data/Salary_Compensation_Schedule.xlsx`


## PivotTable Designs

* Employee salary analysis: `Pivot_Tables/Employee_Salary_Analysis.xlsx`
* Department-wise salary distribution: `Pivot_Tables/Department_Wise_Salary_Distribution.xlsx`
* Grade level-wise salary distribution: `Pivot_Tables/Grade_Level_Wise_Salary_Distribution.xlsx`
* Top 10 highest-paid employees: `Pivot_Tables/Top_10_Highest_Paid_Employees.xlsx`
* Department-wise average salary by grade level: `Pivot_Tables/Department_Wise_Average_Salary_by_Grade_Level.xlsx`


## Dynamic Salary Calculation

* Housing allowance: `=IF(G2="Semi Senior", 0.15*E2, IF(G2="Senior", 0.20*E2, IF(G2="Manager", 0.25*E2, IF(G2="Director", 0.30*E2, 0))))`
* Transport allowance: `=IF(G2="Semi Senior", 0.10*E2, IF(G2="Senior", 0.15*E2, IF(G2="Manager", 0.20*E2, IF(G2="Director", 0.25*E2, 0))))`
* Leave allowance: `=IF(G2="Semi Senior", 0.05*E2, IF(G2="Senior", 0.10*E2, IF(G2="Manager", 0.15*E2, IF(G2="Director", 0.20*E2, 0))))`
* Meal allowance: `=IF(G2="Semi Senior", 0.05*E2, IF(G2="Senior", 0.10*E2, IF(G2="Manager", 0.15*E2, IF(G2="Director", 0.20*E2, 0))))`
* Utility allowance: `=IF(G2="Semi Senior", 0.05*E2, IF(G2="Senior", 0.10*E2, IF(G2="Manager", 0.15*E2, IF(G2="Director", 0.20*E2, 0))))`


## Text Extraction

* Department: `=LEFT(A2,2)`
* Purchase date: `=DATE(RIGHT(MID(A2,3,6),2)+2000,MID(MID(A2,3,6),3,2),LEFT(MID(A2,3,6),2))`
* Asset category: `=RIGHT(A2,4)`


## Commit Messages

* Initial commit: Added employee data, PivotTable designs, dynamic salary calculation, and text extraction formulas.
* Updated PivotTables for department-wise salary distribution.
* Added data visualization using bar charts.



## Acknowledgments

* Ladies in Tech Africa organization
