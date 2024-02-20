# sql-challenge

# Pewlett Hackard Employee Analysis (1980's & 1990's)

Data Enginerring/Modeling Summary
This project looks into the workforace of PH during the 1980s 1990s.It shows company data in CSV files and imported into PostgresSQL database and structured into various tables:

-titles: Contains job titles and their corresponding IDs.

-departments: Holds department names and IDs.

employees: Provides demographic details of employees, including employee ID, title ID, name, birthdate, sex, and date of hire.

salaries: Records the salaries of all employees indexed by employee ID.

dept_employee: Establishes links between employees and their respective department(s) based on department number.

dept_manager: Connects employees to their respective departments, specifically for those holding managerial positions.

Refer to the EmpSQLTable-ERD image linking to EMP-Table-Schemata file that represents the tables schemas. The EmployeeSQL file shows the analysis of as listed below.

Data Analysis Summary
This database was queried to address several inquiries:

1)Display employee number, last name, first name, sex, and salary for each employee.

2)List the first name, last name, and hire date of employees hired in 1986.

3)Present managers of each department alongside their department number, department name, employee number, last name, and first name.

4)Show the department number for each employee, along with their employee number, last name, first name, and department name.

5)List first name, last name, and sex of employees named Hercules with last names beginning with the letter B.

6)Display all employees in the Sales department, including their employee number, last name, and first name.

7)Include all employees in the Sales and Development departments, along with their employee number, last name, first name, and department name.

8)Provide frequency counts, in descending order, of all employee last names (i.e., the number of employees sharing each last name).
