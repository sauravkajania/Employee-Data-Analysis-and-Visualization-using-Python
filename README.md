# Employee Data Analysis and Visualization using Python

## Project Overview
This project focuses on analyzing and visualizing employee data using Python libraries such as **Pandas** and **Matplotlib**. The dataset includes employee information like ID, name, department, salary, and hire date. The goal is to extract insights such as salary distribution, hiring patterns, department-wise employee count, and more.

---

## Technologies Used
- Python
- Pandas
- Matplotlib

---

## Dataset
The dataset (`employees.csv`) contains the following columns:
- `EMPLOYEE_ID`
- `FIRST_NAME`
- `DEPARTMENT_ID`
- `SALARY`
- `HIRE_DATE`
- And possibly other related employee attributes

> File Path: `employees.csv`

---

## Key Operations Performed
1. **Data Loading**: Using `pandas.read_csv()` to load the dataset.
2. **Missing Value Handling**: Filled missing values with `"Unknown"`.
3. **Basic Exploration**:
   - Displayed top and bottom rows.
   - Checked for null values.
   - Found maximum, minimum, mean, and median salaries.
   - Counted unique employee names.
4. **Data Transformation**:
   - Converted `EMPLOYEE_ID` to integer.
   - Added a new column `SALARY_HIKE` with a 10% salary increase.
   - Removed duplicates.
5. **Data Visualization**:
   - **Histogram**: Distribution of hire dates.
   - **Scatter Plot**: Relationship between salary and department.
   - **Bar Chart**: Salary comparison.
6. **Grouping and Filtering**:
   - Grouped by hire date to find average salary.
   - Filtered employees with salary greater than 5500.
   - Counted employees per department.
7. **Export**: Saved the cleaned and updated dataset to `New_Employee.csv`.

---

## Sample Visualizations
- **Experience Chart**: Histogram of employee hire dates.
- **Salary vs Department**: Scatter plot showing salary distribution across departments.
- **Bar Graph**: Comparison of employee salaries.

---

## Output Files
- `New_Employee.csv`: Cleaned and updated employee dataset with new salary values.

---

## How to Run
1. Make sure Python is installed.
2. Install required libraries if not already available:
   ```bash
   pip install pandas matplotlib
   ```
3. Place the employees.csv in the correct file path or modify the script path accordingly.
4. Run the script:
   ```bash
   python main.py
   ```

---
