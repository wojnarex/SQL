# SQL

### UNION vs UNION ALL
- UNION ALL command is equal to UNION command, except that UNION ALL selects all the values. The difference between Union and Union all is that Union all will not eliminate duplicate rows, instead it just pulls all the rows from all the tables fitting your query specifics and combines them into a table.
'
SELECT City FROM Customers
UNION ALL
SELECT City FROM Suppliers
ORDER BY City;
'
