# Employee_Database
Module-7-Challenge-SQL

# Overview of the analysis:
Determine the number of retiring employees with title, and identify employees who are eligible to participate in a mentorship program.

# Results:
Attached file name ‘ret_titles.cvs’ is with the employee number, first name, last name, title, from date and to date of columns for the employees who were born between 1952 and 1955. The total is 54,722.

Attached file name ‘unique_titles.cvs’ is with  the employee number, first name, last name, from date and to date and title of columns for the employee who is left the company and who were born between 1952 and 1955.   The total is 33118. 

Below is the list from file name ‘retiring_title.csv’, the total count by the title is 33118.
count	title
13651	Senior Engineer
12872	Senior Staff
2711	Engineer
2022	Staff
1609	Technique Leader
251	Assistant Engineer
2	Manager

Attached ‘mentorship.cvs’ is is with  the employee number, first name, last name, from date, birth date, from date, to date and title of columns is the list of employees eligible for potential mentorship program because of the birth date follows in between 1965-01-01 and 1965-12-31.  The total is 2382.

# Summary:
The total 54,722 employees were eligible to retire  due to born between 1952 and 1955, but since 33,118 employee has left the company it remains 21,604 from which 2,382 where born in the year 1965. Company still has 19,222 eligible retire employee born between 1952 and 1954.

The table name "mentorship" contains total 2383 rows with the title of employees who were born in year 1965. This table also contains the same
employee whose title changed with the from date.

The total number of rows are 33118 for the table "emp_info". This table contains the salaries of employees born in the year 1965.
