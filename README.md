# task5
This set of queries demonstrates how to perform different types of SQL joins between the STUDENT and DEPARTMENT_INFO tables using the common column DEPARTMENT.

INNER JOIN: Returns only the students whose departments exist in the DEPARTMENT_INFO table.

LEFT JOIN: Returns all students along with their department details if available; unmatched departments show NULL.

RIGHT JOIN: Returns all departments and the students in them; departments with no students show NULL.

FULL OUTER JOIN: Returns all students and all departments, including unmatched rows from both tables with NULL values where no match exists
