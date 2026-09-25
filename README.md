# Employee Data Validation in Excel

## 📌 Overview

This project demonstrates how Excel Data Validation can be used to create a clean, consistent, and reliable employee dataset.

The dataset contains 18 sample employee records with details such as Employee ID, Name, Department, Gender, Age, Join Date, and Salary.

## 🎯 Objectives

- Create a structured employee dataset
- Maintain consistency in data entry
- Create dropdown lists for categorical data
- Restrict age to valid values
- Validate employee joining dates
- Ensure salary values are positive
- Add input messages and error alerts
- Test validation rules using valid and invalid entries

## 📊 Dataset Columns

| Column | Description |
|---|---|
| Employee ID | Unique ID assigned to each employee |
| Name | Employee name |
| Department | Employee's department |
| Gender | Employee gender |
| Age | Employee age |
| Join Date | Employee joining date |
| Salary | Employee salary |

## 🔧 Data Validation Rules

### Department
Dropdown options:
- HR
- Sales
- IT
- Finance
- Operations

### Gender
Dropdown options:
- Male
- Female
- Other

### Age
- Whole number
- Minimum: 18
- Maximum: 65

### Join Date
- Valid date
- From 01/01/2000
- Up to the current date

### Salary
- Positive number
- Greater than 0

## ⚠️ Input Messages and Error Alerts

Input messages were added to guide users during data entry.

Error alerts were configured to prevent invalid values from being entered.

## 🧪 Testing

The validation rules were tested using both valid and invalid entries.

Examples of invalid entries tested:

- Age below 18
- Age above 65
- Future joining date
- Zero salary
- Negative salary
- Invalid department
- Invalid gender

## 🛠️ Tools Used

- Microsoft Excel
- Data Validation
- Excel Tables

## 📁 Project File

`Employee_Data_Validation.xlsx`

## 📌 Outcome

The project demonstrates how Excel Data Validation can improve data quality, reduce manual entry errors, and maintain consistency in datasets prepared for further analysis.
