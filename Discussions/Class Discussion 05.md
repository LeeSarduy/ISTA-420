Lee H. Sarduy                                                                                                                                               Chapter 3 - SQL

8/14/2017                                                                                                                                                    Pages 103-123

**Homework**

**(Lesson Plan 5)**

**1. In general, why would you even want to join two (or more) tables together? This is a good time to think about the nature of relational algebra**.

**2. Describe in your own words the output from an inner join.**

So basically INNER JOIN will return results from a select statement where two tables have fields in common but it will not return results if the tables have nothing in common.

The INNER JOIN creates a new result table by combining column values of two tables (table1 and table2) based upon the join-predicate. The query compares each row of table1 with each row of table2 to find all pairs of rows which satisfy the join-predicate. When the join-predicate is satisfied, column values for each matched pair of rows of A and B are combined into a result row.

**3.**** Describe in your own words the output from an outer join.**

So, OUTER JOINS will not only return the inner results where there are matches between the two tables but it will also return the outer result where no matches were found.

**4.**** Describe in your own words the output from an cross join.**

Is basically the result of multiplying the number of rows in one table by the number of rows in the other table and you will get every possible combination.

**5. A convenient mnemonic for remembering the various joins is \Ohio.&quot; Why is this true?**

**6. Give an example of a composite join.**
