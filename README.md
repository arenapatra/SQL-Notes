Problem Statement:
- You're a Data Analyst at Amazon Fresh tasked with studying the Farmer’s Market.
- You'll be working with a Farmer’s Market database.

Relationships in a Schema:
- Different types of relationships in tables: One-to-One, One-to-Many, Many-to-Many.
- Entity-relationship diagrams depict relationships.
One-to-one relationship occurs when each row in Table 1 has only one related row in Table 2.
One-to-many occurs when one record in Table 1 is related to one or more records in Table 2.
Many-to-many occurs when multiple records in one table are related to multiple records in another table.

Understanding ER Diagram:
- ER diagrams show entities, attributes, keys, and relationships.
- Used interchangeably with the DB schema.

SQL Commands:
- SQL stands for Structured Query Language.
- Types: DDL (Data Definition), DML (Data Manipulation), TCL (Transaction Control), DQL (Data Query), DCL (Data Control).

SELECT Query:
- Syntax: SELECT [columns]
FROM [schema.table]
WHERE [conditions]
ORDER BY [columns]
LIMIT [number]
OFFSET [number]

- SELECT retrieves data, FROM specifies the table, WHERE sets conditions.
- Good practice to specify column names, not use asterisk (*).

ORDER BY:
- Used to sort query results.
- ASC sorts ascending, DESC sorts descending.
- Multiple columns can be used for sorting.

LIMIT & OFFSET:
- LIMIT limits the number of rows returned.
- OFFSET skips rows before the result set.
- Useful for pagination and top results.
- LIMIT [no_of_first_n_rows_to_be_returned] OFFSET [no_of_rows_to_skip]

Inline Calculation:
- Perform calculations on columns within SELECT queries.
- Use operators (+, -, *, /) for arithmetic.
- Create aliases for calculated columns with AS.

Alias (AS):
- Assign meaningful names to calculated columns.
- Use AS after the calculation.
- Enclose aliases with single quotes if they contain spaces.
- Syntax: 
SELECT column1, column2....
FROM table_name AS alias_name
WHERE [condition];

ROUND() function:
- Used to round numeric values.
- Syntax: ROUND(value, decimal_places).
- Example: ROUND(5.456, 2) returns 5.46.

Functions in SQL:
- Functions modify raw values in queries.
- Syntax: FUNCTION_NAME(parameters).
- Examples: ROUND(), CEIL(), FLOOR().

Additional Functions:
- CEIL(): Rounds up to the nearest integer.
- FLOOR(): Rounds down to the nearest integer
