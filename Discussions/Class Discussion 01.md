Lee H. Sarduy                                                                                                                                               Chapter 1 - SQL

8/7/2017                                                                                                                                                    Pages 1-26

**Homework**

**(Lesson Plan 1)**



**1. Give an informal definition of database as used in the expression \relational database management**

**system.&quot;**

Software.

**2. Give an informal definition of database as used in the expression \Human Resources database.&quot;**

Data in the database

**3. Give an informal definition of entity integrity.**

Making each row unique

**4. Give an informal definition of referential integrity.**

Attributes with foreign keys contain only data that appears in the referencing key&#39;s attributes

**5. What is a relation as defined in the textbook? A one word answer to this question is sufficient.**

A set.

**6. Is this table in first normal form? Why or why not? If it is not, how would you change it?**

**create table faculty (**

**facID int primary key,**

**facName text,**

**facCreds text);**

**facID facName facCreds**



**7. Is this table in second normal form? Why or why not? If it is not, how would you change it?**

**create table pets (**

**ownerID int primary key,**

**petID int primary key,**

**ownerFirstName text,**

**ownerLastName text,**

**petName text,**

**petType text);**



**8. Is this table in third normal form? Why or why not? If it is not, how would you change it?**

**create table friends (**

**friendID int primary key,**

**friendName text,**

**friendStreet text,**

**friendCity text,**

**friendState text,**

**friendZip text);**

**9. What is an OLTP database? What operations is it optimized for?**

A database used for data entry and not reporting/insert, update, and delete data.

**10. What is a star schema? What operations is it optimized for?**

Designed based on a fact table which contains the elements of interest/it is optimized for data analysis.
