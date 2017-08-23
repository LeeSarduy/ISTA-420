Lee H. Sarduy                                                                                                                                             Chapter 2 - SQL

8/9/2017                                                                                                                                                    Pages 49-73

**Homework**

**(Lesson Plan 3)**

1. **List the order of execution of a SQL query.**

_FROM, WHERE, GROUP BY, HAVING, SELECT, ORDER BY_

1. **What does the**  **from**  **clause do?**

In this clause, you specify the name of the tables you want to query and table operators that operate on those tables.

1. **What does the**  **where**  **clause do?**
  1. In the _WHERE_ clause, you specify a predicate or logical expression to filter the rows returned by the _FROM_ phase. Only rows for which the logical expression evaluates to _TRUE_ are returned by the _WHERE_ phase to the subsequent logical query processing phase.

1. **What does the**  **group by**  **clause do?**
  1. Expressions that are not encapsulated within an aggregate function and must be included in the **GROUP BY Clause** at the end of the **SQL** statement. This is an aggregate function such as the SUM, COUNT, MIN, MAX, or AVG functions. This is the column or expression that the aggregate\_function will be used on.

1. **What does the**  **having**  **clause do?**
  1. A **HAVING clause** in **SQL** specifies that an **SQL** SELECT statement should only return rows where aggregate values meet the specified conditions. It was added to the **SQL** language because the WHERE keyword could not be used with aggregate functions.

1. **What does the**  **select**  **clause do?**
  1. The **SQL SELECT statement** returns a result set of records from one or more tables. A **SELECT statement** retrieves zero or more rows from one or more database tables or database views. In most applications, **SELECT** is the most commonly used data **query** language (DQL) command. ... WHERE specifies which rows to retrieve.

1. **What does the**  **distinct**  **keyword do?**
  1. The **SQL** SELECT **DISTINCT** Statement. The SELECT **DISTINCT** statement is used to return only **distinct** (different) values. Inside a table, a column often contains many duplicate values; and sometimes you only want to list the different ( **distinct** ) values.

1. **What does the**  **order by**  **clause do?**
  1. a.The **SQL ORDER BY clause** is used to sort the data in ascending or **descending   order** ,         based on one or more columns.

1. **What does the**  **limit**  **clause do? This is not in the book.**

The **SQL** SELECT **LIMIT** statement is used to retrieve records from one or more tables in a database and **limit** the number of records returned based on a **limit** value.



1. **What does the**  **top**  **clause do?**

The SELECT TOP clause is used to specify the number of records to return.

The SELECT TOP clause is useful on large tables with thousands of records. Returning a large number of records can impact on performance.

1. **What do the**  **off\_set . . . fetch . . .**  **clauses do?**
  1. The OFFSET-FETCH clause provides you with an option to fetch only a window or page of results from the result set. OFFSET-FETCH can be used only with the ORDER BY clause.