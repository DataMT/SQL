# SQL

1. UNION and UNION ALL:
The UNION operator is used to combine the result-set of two or more SELECT statements.
The UNION operator selects only distinct values by default. To allow duplicate values, use UNION ALL.

Explain: 
If some customers or suppliers have the same city, each city will only be listed once, because UNION selects only distinct values. Use UNION ALL to also select duplicate values!

2.The SQL HAVING Clause
The HAVING clause was added to SQL because the WHERE keyword could not be used with aggregate functions
