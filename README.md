# Module 9- sql-challenge
This challenge will display data modeling, data engineering, and data analysis of a fictional company, Pewlett Hackard.

Pewlett Hackard's employee and department files are to be examined to aid their hiring process. 

## Data Modeling 
QuickDBD is used to sketch an Entity Relationship Diagram for Pewlwtt Hackard.
![Data Modeling ](https://user-images.githubusercontent.com/121995835/228045206-e0fa6b98-1c31-425c-9127-f1cf99c88e9b.png)

## Data Engineering 
Tables have been createed for each of the 6 CSV files from Pewlett Hackard in this Table Schema. (Also located in the EmployeeSQL folder.)


	FOREIGN KEY (Emp_no) REFERENCES EMPLOYEES(Emp_no),
