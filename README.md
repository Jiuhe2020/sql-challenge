# Employee Database: A Mystery in Two Parts
## Challenge Instructions
This project utilizes Data Engineering and Data Analysis to build a SQL database of employees of the corporation called Pewlett Hackard from the 1980s and 1990s. There are six CSV files holding the data of employees. The SQL tables were designed and the data in the CSVs were successfully imported into a SQL database.

## Data Engineering
Inspect the CSVs and sketch out an ERD of the tables. After creating a table schema for each of the six CSV files, import each CSV file into the corresponding SQL table.

## Data Analysis
- List the following details of each employee: employee number, last name, first name, sex, and salary.
- List first name, last name, and hire date for employees who were hired in 1986.
- List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
- List the department of each employee with the following information: employee number, last name, first name, and department name.
- List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
- List all employees in the Sales department, including their employee number, last name, first name, and department name.
- List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
- In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

## BONUS
A visualization of the data was generated by taking the following steps:
- Import the SQL database into Pandas.
- Create a histogram to visualize the most common salary ranges for employees.
- Create a bar chart of average salary by title.

## List of Files
1. employee_ERD.png: an image file of the ERD
2. employee_schema.sql: a .sql file of the table schemata
3. employee_query.sql: a .sql file of the queries
4. employee.ipynb: a Jupyter Notebook of the bonus analysis

---
### Copyright
Jiuhe Zhu © 2020. All Rights Reserved.
