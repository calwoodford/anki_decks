<div align="center">
  <img height="60" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Sql_data_base_with_logo.png/800px-Sql_data_base_with_logo.png?20210130181641">
  <h1>SQL Questions and Answers</h1>
    <br><br>

</div>

###### Question 1.

Why would you use a SQL database instead of a JSON?

<details><summary><b>Answer</b></summary>
<p>

SQL databases are ideal for structured data with well-defined schemas and relationships, while JSON is more flexible and suited for semi-structured or unstructured data.

</p>
</details>

<br><br>

###### Question 2.

What is Postgres?

<details><summary><b>Answer</b></summary>
<p>

Postgres, short for PostgreSQL, is an open-source relational database management system (RDBMS) known for its robustness and extensibility.

</p>
</details>

<br><br>

###### Question 3.

What is the difference between Postgres and SQL?

<details><summary><b>Answer</b></summary>
<p>

SQL is a language used to manage and query relational databases, while Postgres is a specific RDBMS that uses SQL as its query language.

</p>
</details>

<br><br>

###### Question 4.

What does SQL stand for?

<details><summary><b>Answer</b></summary>
<p>

SQL stands for "Structured Query Language," which is a domain-specific language used to manage and manipulate relational databases.

</p>
</details>

<br><br>

###### Question 5.

What is a relational database?

<details><summary><b>Answer</b></summary>
<p>

A relational database is a type of database that organizes data into structured tables with defined relationships between them.

</p>
</details>

<br><br>

###### Question 6.

What is the benefit of using a relational database?

<details><summary><b>Answer</b></summary>
<p>

Relational databases provide data integrity, support complex queries, and enable efficient data retrieval due to their structured nature.

</p>
</details>

<br><br>

###### Question 7.

What is a primary key?

<details><summary><b>Answer</b></summary>
<p>

A primary key is a unique identifier for a record in a table. It ensures that each row is uniquely identifiable.

</p>
</details>

<br><br>

###### Question 8.

What is a foreign key?

<details><summary><b>Answer</b></summary>
<p>

A foreign key is a field in a table that links to the primary key of another table, establishing a relationship between the tables.

</p>
</details>

<br><br>

###### Question 9.

Postgres, MySQL, Amazon RDS, Microsoft SQL Server, and Oracle are all what?

<details><summary><b>Answer</b></summary>
<p>

They are all examples of relational databases.

</p>
</details>

<br><br>

###### Question 10.

Is Postgres open or closed source?

<details><summary><b>Answer</b></summary>
<p>

Postgres is open source, meaning its source code is publicly available for inspection and modification by the community.

</p>
</details>

<br><br>

###### Question 11.

What is the role of SQL?

<details><summary><b>Answer</b></summary>
<p>

SQL is used to define, manipulate, and query data in relational databases.

</p>
</details>

<br><br>

###### Question 12.

What are column and table names known as?

<details><summary><b>Answer</b></summary>
<p>

Column and table names are known as identifiers in SQL.

</p>
</details>

<br><br>

###### Question 13.

How to select an entire table?

<details><summary><b>Answer</b></summary>
<p>

Use the `SELECT *` statement. Example: `SELECT * FROM tableName;`

</p>
</details>

<br><br>

###### Question 14.

Do the keywords have to be capitalized in SQL?

<details><summary><b>Answer</b></summary>
<p>

No, SQL keywords are not case-sensitive, but it's a common convention to capitalize them for clarity.

</p>
</details>

<br><br>

###### Question 15.

What is normalisation?

<details><summary><b>Answer</b></summary>
<p>

Normalization is the process of organizing data in a database to reduce redundancy and improve data integrity.

</p>
</details>

<br><br>

###### Question 16.

What is an ERD, and what does it do?

<details><summary><b>Answer</b></summary>
<p>

An ERD (Entity-Relationship Diagram) is a visual representation of the relationships between entities (tables) in a database.

</p>
</details>

<br><br>

###### Question 17.

How can you refer to a column in a table?

<details><summary><b>Answer</b></summary>
<p>

You can refer to a column in the format `tableName.columnName`. Example: `SELECT tableName.columnName FROM tableName;`

</p>
</details>

<br><br>

###### Question 18.

How might `SELECT` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`SELECT` is used to retrieve data from one or more columns in a table. Example: `SELECT column1, column2 FROM tableName;`

</p>
</details>

<br><br>

###### Question 19.

How might `FROM` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`FROM` specifies the table or tables from which to retrieve data. Example: SELECT \* FROM tableName;

</p>
</details>

<br><br>

###### Question 20.

How might `WHERE` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`WHERE` is used to filter rows based on a specified condition. Example: `SELECT * FROM tableName WHERE condition;`

</p>
</details>

<br><br>

###### Question 21.

How might `ORDER` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`ORDER` is not used by itself but is often followed by `BY` to sort results. Example: `SELECT * FROM tableName ORDER BY columnName;`

</p>
</details>

<br><br>

###### Question 22.

How might `ORDER BY` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`ORDER BY` is used to sort results in ascending (ASC) or descending (DESC) order. Example: `SELECT * FROM tableName ORDER BY columnName ASC;`

</p>
</details>

<br><br>

###### Question 23.

How might `SELECT *` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`SELECT *` retrieves all columns from a table. Example: `SELECT * FROM tableName;`

</p>
</details>

<br><br>

###### Question 24.

How might `INNER JOIN` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`INNER JOIN` combines rows from two or more tables based on a related column. Example: `SELECT * FROM table1 INNER JOIN table2 ON table1.column = table2.column;`

</p>
</details>

<br><br>

###### Question 25.

How might `ON` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`ON` specifies the join condition when using JOIN operations. Example: `ON table1.column = table2.column;`

</p>
</details>

<br><br>

###### Question 26.

How might `LIMIT` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`LIMIT` restricts the number of rows returned in the result set. Example: `SELECT * FROM tableName LIMIT 10;`

</p>
</details>

<br><br>

###### Question 27.

How might `AND` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`AND` combines multiple conditions in a WHERE clause. Example: `SELECT * FROM tableName WHERE condition1 AND condition2;`

</p>
</details>

<br><br>

###### Question 28.

How might `OR` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`OR` allows you to retrieve rows that meet either of two conditions in a WHERE clause. Example: `SELECT * FROM tableName WHERE condition1 OR condition2;`

</p>
</details>

<br><br>

###### Question 29.

How might `IN` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`IN` is used to specify multiple values for a column in a WHERE clause. Example: `SELECT * FROM tableName WHERE column IN (value1, value2);`

</p>
</details>

<br><br>

###### Question 30.

How might `NOT IN` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`NOT IN` retrieves rows that do not match any value in a list. Example: `SELECT * FROM tableName WHERE column NOT IN (value1, value2);`

</p>
</details>

<br><br>

###### Question 31.

How might `BETWEEN` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`BETWEEN` is used to filter rows within a specified range. Example: `SELECT * FROM tableName WHERE column BETWEEN value1 AND value2;`

</p>
</details>

<br><br>

###### Question 32.

How might `NOT BETWEEN` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`NOT BETWEEN` filters rows outside a specified range. Example: `SELECT * FROM tableName WHERE column NOT BETWEEN value1 AND value2;`

</p>
</details>

<br><br>

###### Question 33.

How might `DISTINCT` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`DISTINCT` retrieves unique values from a column. Example: `SELECT DISTINCT column FROM tableName;`

</p>
</details>

<br><br>

###### Question 34.

How might `ASC`/`DESC` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`ASC` and `DESC` are used with `ORDER BY` to specify ascending or descending sorting. Example: `SELECT * FROM tableName ORDER BY column ASC;`

</p>
</details>

<br><br>

###### Question 35.

How might `OFFSET` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`OFFSET` is used to skip a specified number of rows before retrieving results. Example: `SELECT * FROM tableName OFFSET 5;`

</p>
</details>

<br><br>

###### Question 36.

How might `JOIN` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`JOIN` combines rows from two or more tables based on related columns. Example: `SELECT * FROM table1 JOIN table2 ON table1.column = table2.column;`

</p>
</details>

<br><br>

###### Question 37.

How might `INNER JOIN` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`INNER JOIN` combines rows where there is a match in both tables based on the join condition. Example: `SELECT * FROM table1 INNER JOIN table2 ON table1.column = table2.column;`

</p>
</details>

<br><br>

###### Question 38.

How might `LEFT JOIN` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`LEFT JOIN` returns all rows from the left table and matching rows from the right table. Example: `SELECT * FROM table1 LEFT JOIN table2 ON table1.column = table2.column;`

</p>
</details>

<br><br>

###### Question 39.

How might `RIGHT JOIN` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`RIGHT JOIN` returns all rows from the right table and matching rows from the left table. Example: `SELECT * FROM table1 RIGHT JOIN table2 ON table1.column = table2.column;`

</p>
</details>

<br><br>

###### Question 40.

How might `FULL JOIN` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`FULL JOIN` returns all rows when there is a match in either the left or right table. Example: `SELECT * FROM table1 FULL JOIN table2 ON table1.column = table2.column;`

</p>
</details>

<br><br>

###### Question 41.

How might `NULL` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`NULL` is used to represent missing or unknown data in SQL queries. Example: `SELECT * FROM tableName WHERE column IS NULL;`

</p>
</details>

<br><br>

###### Question 42.

How might `AS` be used in a query?

<details><summary><b>Answer</b></summary>
<p>

`AS` is used to alias columns or tables, providing a temporary name for them in the result set. Example: `SELECT column1 AS aliasName FROM tableName;`

</p>
</details>

<br><br>
