# Week 09 -  Employee Database: A Mystery in two Parts  <!-- omit in toc -->

- [Background](#background)
- [Section 1 - Data Modeling](#section-1---data-modeling)
- [Section 2 - Data Engineering](#section-2---data-engineering)
- [Section 3 Data Analysis.](#section-3-data-analysis)

## Background

In this assignment, I was asked to take 6 csv files and look at employees of a fictional company Pewlett Hackard. I was to do the following:

 - Data Modeling
 - Data Engineering
 - Data Analysis

## Section 1 - Data Modeling

I inspected the provided CSVs and sketched out an ERD of the tables.
I used freeware at quickdatabasedesigns.com in order to create an ERD regarding the SQL database.  I assigned primary keys, along with foreign keys relating back to employees.emp_no and departments.dept_no. 
Here is the results of the ERD:
![Data_Modeling_ERD](EmployeeSQL/ERD_Diagram.png)

## Section 2 - Data Engineering

For this section, I used the results of the ERD to create a file Schema.txt which can be found in the EmployeeSQL file folder. This file shows how I chose to design the database. 

## Section 3 Data Analysis.

Once I had created a Database using Postgres and PGAdmin 4, I answered the following questions by performing SQL queries:


1. List the following details of each employee: employee number, last name, first name, gender, and salary.

2. List employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name, and start and end employment dates.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List all employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

