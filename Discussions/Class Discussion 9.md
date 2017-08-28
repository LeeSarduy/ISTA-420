Lee H. Sarduy                                                                                                                                       Chapter 6 – SQL
8/22/2017                                                                                                                                              Pages 193-204
**Homework**
**(Lesson Plan 9)**

1. **What does a set operator do?**
-Operators that combine rows from two query results.

1. **What are the general requirements of a set operator**
-Two input queries must produce results with the same number of columns, and corresponding columns must have compatible data types.

1. **What is a Venn Diagram? This is not in the book.**
A diagram that shows all possible logical relations between a finite collection of different sets.

1. **Draw a Venn Diagram of the UNION operator. What does it do?**
-Unifies the results of two input queries.

1. **Draw a Venn Diagram of the UNION ALL operator. What does it do?**
Unifies the two input query results without attempting to remove duplicates.

1. **Draw a Venn Diagram of the INTERSECT operator. What does it do?**
-Returns only the rows that are common to the results of the two input queries.

1. **If SQL Server supported the INTERSECT ALL operator, what would it do?**
-It would return the number of duplicate rows matching the lower value in both inputs.

1. **Draw a Venn Diagram of the EXCEPT operator. What does it do?**
-Returns distinct rows that appear in the first set but not the second.

1. **If SQL Server supported the EXCEPT ALL operator, what would it do?**
-It would return occurrences of a row from the first multiset that do not have a corresponding occurrence in the second.

1. **What is the precedence of the set operators?**
-The precedence of the set operators is the INTERSECT operator precedes UNION and EXCEPT, and UNION and EXCEPT are evaluated in order of appearance. Using the ALL variant doesn&#39;t change the precedence.