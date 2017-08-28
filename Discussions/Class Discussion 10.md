Lee H. Sarduy                                                                                                                                       Chapter 7 – SQL
8/22/2017                                                                                                                                              Pages 213-230
**Homework**
**(Lesson Plan 10)**

1. **What is a window function?**
-Computes a scalar result value based on a calculation against a subset of rows.

1. **What does PARTITION do?**
-The window-partition clause (PARTITION BY) restricts the window to the subset of rows that have the same values in the partitioning columns as in the current row.

1. **What does ORDER BY do?**
-The window ordering gives meaning to the rank.

1. **What does ROWS BETWEEN do?**
-A window-frame clause (ROWS BETWEEN &lt;top delimiter&gt; AND &lt;bottom delimiter&gt;) filters a frame, or a subset, of rows from the window partition between the two specified delimiters.

1. **What is a ranking window function? Why would you use it? Give an example.**
-Ranks each row with respect to others in the window. To identify an object/RANK

1. **What is an offset window function? Why would you use it? Give an example.**
**-** Returns an element from a row that is offset from the current row or at the beginning or end of a window frame. To identify FIRST\_VALUE

1. **What do LEAD and LAG DO?**
-The LAG and LEAD functions support window partitions and window order clauses.

1. **What do FIRST VALUE and LAST VALUE do?**
-You use the FIRST\_VALUE and LAST\_VALUE functions to return an element from the first and last rows in the window frame, respectively.

1. **What is an aggregate window function? Why would you use it? Give an example.**
-Aggregate the rows in the defined window. They support window-partition, window-order, and window-frame clauses.

1. **What is a pivot table and what does it do?**