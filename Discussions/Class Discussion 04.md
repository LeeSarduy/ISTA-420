Lee H. Sarduy                                                                                                                                               Chapter 2 - SQL

8/7/2017                                                                                                                                                       Pages 73-93

**Homework**

**(Lesson Plan 4)**

1. **What is a data type? Why do we have data types?**
  1. A data-type is a property that specifies the type of data you can put in your table. Data types help to tell the computer what to do or what to expect.

1. **What is a collation? Name four elements of a collation.**
  1. Collation is a property of character data that encapsulates several aspects: language support, sort order, case sensitivity, accent sensitivity, and more.
  2. \*Case incensitive
  3. \*Accent sencitive

1. **How would you strip whitespace from a string? For example, suppose you had &quot;^^^^Dave^^^^&quot; but wanted only &quot;Dave&quot;.**

To strop whitespace from a string use a combination of LTRIM and RTRIM. For example

-SELECT trim?(rtrim(&quot;   Dave   &quot;));

1. **Suppose you wanted to make a list of every college and university that was called an Institute from the**  **college**  **table. Write the query.**

SELECT name

FROM college

WHERE name like &quot;%institute%&quot;;

1. **How would you find out the index of the first space in a string? For example, the index of the first space in \Barack Hussein Obama&quot; would be 7.**

select charindex(&#39; &#39;, &#39;Barack Hussein Obama&#39;);

1. **How would you select just the first name in a list of the presidents? First names can be an arbitrary length, from &quot;Cal&quot; to &quot;Benjamin.&quot;**

To select just the first name in a list of presidents with arbitrary first name length and the names are separated by spaces, use a combination of LEFT and CHAINDEX. For example:

SELECT left(name, charindex(&#39; &#39;, name)) from presidents;

1. **Payments are due exactly 30 days from the date of the last function. Write a select query that calculates the date of the next payment. Pretend we want to update a column in a database that contains the date of the next payment. We will do this when we write**  **UPDATE**  **queries.**

SELECT dateadd(day, 30, orderdate

1. **Suppose your son or daughter wants to run a query every day that tells them the number of days until their 16th birthday. Write a select query that does this.**

select datediff(day, getdate(), dateof16thbirthday);

1. **What function returns the current date? This is very useful in a table that maintains a log of events, such as user logins.**

Getdate()
