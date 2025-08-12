SQL JOIN is used to combine data from two or more tables based on a related column. It allows retrieving meaningful information that spans multiple tables in a relational database.

In relational database design, data is often stored in separate tables to reduce redundancy and improve organization. JOIN operations help merge this data back together when querying.

Types of SQL Joins:

INNER JOIN – Returns only matching rows from both tables.

LEFT JOIN – Returns all rows from the left table and matching rows from the right table; unmatched rows in the right table appear as NULL.

RIGHT JOIN – Returns all rows from the right table and matching rows from the left table; unmatched rows in the left table appear as NULL.

FULL JOIN – Returns all rows from both tables, with NULL where no match exists (simulated with UNION in MySQL).
