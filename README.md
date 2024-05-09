## SQL Challenge

## Background
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files. in this project, tables were designed to hold the data from the CSV files, then the CSV files were imported into an SQL database, and then answers were provoded for the challenge questions about the data. Data modeling, data engineering, and data analysis, were performed respectively.


## Instructions
This challenge is divided into three parts: data modeling, data engineering, and data analysis.


### Data Modeling
Inspect the CSV files, then sketch an Entity Relationship Diagram of the tables.

### Data Engineering
Create a table schema for each of the six CSV files. 

- Specify the data types, primary keys, foreign keys, and other constraints.
- For the primary keys, verify that the column is unique. Otherwise, create a composite key link to an external site., which takes two primary keys to uniquely identify a row.
- Create the tables in the correct order to handle the foreign keys.
- Import each CSV file into its corresponding SQL table.


### Data Analysis
1. List the employee number, last name, first name, sex, and salary of each employee.

2. List the first name, last name, and hire date for the employees who were hired in 1986.

3. List the manager of each department along with their department number, department name, employee number, last name, and first name.

4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

5. List the first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

6. List each employee in the Sales department, including their employee number, last name, and first name.

7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

### References

Tutorialspoint (2024). How to apply EXTRACT() function with WHERE Clause on the dates stored in MySQL table? Retrieved from https://www.tutorialspoint.com/How-to-apply-EXTRACT-function-with-WHERE-Clause-on-the-dates-stored-in-MySQL-table
