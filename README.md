# Data Cleaning and Transformation in R

## Project Overview
This project focuses on cleaning and preparing a dataset for analysis using the R programming language. The dataset contains employee information such as names, dates of birth (DOB), ages, departments, salaries, joining dates, and performance scores. The goal is to handle missing values, standardize column formats, and create new derived columns for further analysis.

---

## Dataset
The original dataset is provided in an Excel file (`Employees data.xlsx`) with the following columns:
- **Name**: Employee names
- **DOB**: Date of birth
- **Age**: Employee age
- **Department**: Department where the employee works
- **Salary**: Employee salary
- **Joining Date**: Date the employee joined the organization
- **Performance Score**: Employee performance score

---

## Steps Performed
1. **Load and Inspect the Data**:
   - Load the dataset from the Excel file.
   - Inspect the dataset for structure, missing values, and data types.

2. **Handle Missing Values**:
   - Fill missing names with "Unknown".
   - Fill missing departments with "Unassigned".
   - Impute missing salaries with the average salary.
   - Drop rows where Age or DOB is missing.

3. **Standardize Column Formats**:
   - Convert DOB and Joining Date to Date format.
   - Convert Performance Score to a factor variable.

4. **Create New Derived Columns**:
   - Calculate employee tenure (years since joining).
   - Create an "Experience Level" column based on tenure.

---

## Files in the Repository
- **`data_cleaning.R`**: R script containing the code for data cleaning and transformation.
- **`Employees data.xlsx`**: Original dataset in Excel format.
- **`cleaned_employees.csv`**: Final cleaned dataset after transformation.

---

## How to Use
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
