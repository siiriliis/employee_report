# Employee Report
This project is about employee turnover and satisfaction survey results.
## Problem Statement
HR department wants an overview of active and left employees over time and results of satisfaction survey

## Plan
I will create a Power BI report to give this overview.  

## Data 
HR department gave me two files:  
- "Employee_Satisfaction_Survey.xlsx"  
- "HR_Dataset.CSV"

 ### Data Cleaning 
 I checked data for uniquensess, formats and outliers through PowerQuery
 Survey dataset didn't have a unique key column. I created a new column "AnsverKey" which combined "Question Round" and "Answer ID"
 In HR dataset, I removed columns with personal data: "First Name", "Last Name" and "Email". Also removed the column "Employment Status" as the data in that column was not up to date according to the HR department.
 Column "Salary" was changed to Decimal Number format

## Analysis

## Recommendations
