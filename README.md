# SQL-Challenge<br>

Background<br>
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.<br>
For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.<br>

Instructions<br>
This Challenge is divided into three parts: data modeling, data engineering, and data analysis.<br>

Data Modeling<br>

Inspect the CSV files, and then sketch an Entity Relationship Diagram of the tables. To create the sketch, feel free to use a tool like QuickDBDLinks to an external site..<br>

Data Engineering<br>
1.	Use the provided information to create a table schema for each of the six CSV files. Be sure to do the following:<br>
o	Remember to specify the data types, primary keys, foreign keys, and other constraints.<br>
o	For the primary keys, verify that the column is unique. Otherwise, create a composite keyLinks to an external site., which takes two primary keys to uniquely identify a row.<br>
o	Be sure to create the tables in the correct order to handle the foreign keys.<br>

2.	Import each CSV file into its corresponding SQL table.<br>

Data Analysis<br>
1.	List the employee number, last name, first name, sex, and salary of each employee.<br>
2.	List the first name, last name, and hire date for the employees who were hired in 1986.<br>
3.	List the manager of each department along with their department number, department name, employee number, last name, and first name.<br>
4.	List the department number for each employee along with that employee’s employee number, last name, first name, and department name.<br>
5.	List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.<br>
6.	List each employee in the Sales department, including their employee number, last name, and first name.<br>
7.	List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.<br>
8.	List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).<br>

