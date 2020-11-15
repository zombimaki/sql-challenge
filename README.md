# sql-challenge

The SQL Challenge project consisted of the following processes and activities:

1. Created an ERD of the tables to be used in the project. The ERD was created with quickdatabasediagrams.com and the imgage was saved to the EmployeeSQL folder as employee_ERD.png.
2. A SQL file was created that creates the database tables and constraints. The sql file with this code is named schema.sql and is in the EmployeeSQL folder.
3. Manualy imported the csv files into the new tables through PGadmin, paying special attention to the column names and locations.
4. Created the SQL file, data_analysis.sql, in the EmployeeSQL folder with queries to return the following data:
a. Employee number, last name, first name, sex, and salary<br />
b. First name, last name, and hire date for employees who were hired in 1986<br />
c. Department number, department name, the manager's employee number, last name, first name<br />
d. employee number, last name, first name, and department name<br />
e. First name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."<br />
f. All employees in the Sales department, including their employee number, last name, first name, and department name<br />
g. All employees in the Sales and Development departments, including their employee number, last name, first name, and department name<br />
h. In descending order, a listing of the frequency count of employee last names, i.e., how many employees share each last name<br />


#bonus material

The jupyter notebook, bonus.ipynb, was created for the bonus part of this project and performs the following:

1. Makes a connection to the Postgres employee database.
2. Creates dataframes for the salaries, employees, and titles tables and merges them all into the employee_final_df dataframe.
3. Generates a histogram of the employee salaries.
4. Generates a bar chart for average salary by title.
5. Identifes the employee who is employeee number 499942.