What is RDBMS?

In an RDBMS or Relational Database Management System, the data is organised into tables with rows and columns - like it is done in a spreadsheet. The data entered in a row of the table would be associated with its respective column's header, making the data more structured and tidy. The main component of an RDBMS therefore consists of its capability of inputting data as tables and also allowing data interaction and management based on the relationship between the tables. 

In order to better explain this, let's take an example of a 'Soft-Drink refrigerator' as the one that has been displayed below.

Lets assume that the manager of the store that this fridge is set up in, wishes to efficiently manage information related to the various soft drinks such as:
- Name of all the soft-drink brands
- Details related to supplier of the soft-drinks

In order to do so, he could utilise an RDBMS to help him store and manage data in the form of various tables. This could be done by creating one table called "Brand_Names" and another called "Supplier_Details", and populating the related data into these tables. However, in order to check which supplier is in charge of supplying a specific soft-drink, a relation could be easily formed between the 2 tables for relating different brands with their suppliers, in the following way:

<will be attaching video or screenshot or plantuml diagram>

--------

## What is ACID, Explain with example.

ACID Compliance in the context of databases stands for Atomicity, Consistency, Isolation and Durability. These 4 components help with a stronger reliablility and integrity of data transactions, which is a logical unit of work done using database operations such as inserting, deleting or updating data. The components of ACID Compliance can therefore be understood better in the following way:

### Atomicity 
According to this property, the entire transaction is either complete or none of it is. A transaction in this case works as a single unit and cannot be divided into sub-transactions, meaning that either the entire process of data interaction is going to succeed or the entire operation would be aborted and rolled back to the previous state. 

An example of such a case would be when an online transaction of money is done using PhonePay. As per the atomicty of a database, if any part of this process fails after the deduction from the sender's account but before the transfer to recipient's account, then the entire transaction is to be rolled back so that the sender does not lose their money.

### Consistency
The property of Consitency ensures that the data is always available in a consistent state and that the rules set for data interaction, are not being violated during transactions. What this means is that the stored data is to remain reliable and as near accurate as possible. Going back to the previous example of making transactions using PhonePay, such a rule of consistency is that the sender would only be allowed to enter positive digits, when requesting transfer of money. Adding such constraints help keep the data remain in a reliable state. 

### Isolation
According to the rule of Isolation, when operations are performed on the data through multiple transactions from multiple users, the transactions are carried out separately without affecting the other transactions. What this means is that if 2 operations are done on the same data then only one transaction would succeed and that the operation made slightly after would fail. For example, if a seat is being booked for a movie on [BookMyShow](www.bookmyshow.com) then multiple people would not be able to book the same seat and only the transaction that was done first would succeed. Isolation therefore ensures that multiple transactions do not mess up eachother's operations.

### Durability
The durability property states that once a transaction has been carried out, then the data and the operations made would remain in a permanent state. Going back to the previous example of booking a seat for a movie using BookMyShow, the property of durability would ensure that once the transaction or the booking has been made, all the bookings would remain intact even after a server-failure at BookMyShow. Once the transaction has been done, it cannot be undone accidentally until and unless a request is made for it. 

## Explain RDBMS vs DBMS.

As stated before, a Relational Database Management System is a 

RDBMS on the other hand is a type of DBMS, as the name suggest it deals with relations as well as various key constraints. So here we have tables which is called as schema and we have rows which are called as tuples. It also aids in the reduction of data redundancy and the preservation of database integrity. Relational Database Management System is an advanced version of a DBMS. 

Why DBMS Required?
Database management system, as the name suggest, is a management system which is used to manage the entire flow of data, i.e, insertion of data or the retrieval of data, how the data is inserted into the database or how fast the data should be retrieved, so DBMS takes care of all these features, as it maintains the uniformity of the database as well does the faster insertions as well as retrievals.

Why RDBMS Required?


DBMS	RDBMS
DBMS stores data as file.	RDBMS stores data in tabular form.
Data elements need to access individually.	Multiple data elements can be accessed at the same time.
No relationship between data.	Data is stored in the form of tables which are related to each other.
Normalization is not present.	Normalization is present.
DBMS does not support distributed database.	RDBMS supports distributed database.
It stores data in either a navigational or hierarchical form.	It uses a tabular structure where the headers are the column names, and the rows contain corresponding values.
It deals with small quantity of data.	It deals with large amount of data.
Data redundancy is common in this model.	Keys and indexes do not allow Data redundancy.
It is used for small organization and deal with small data.	It is used to handle large amount of data.
Not all Codd rules are satisfied.	All 12 Codd rules are satisfied.
Security is less	More security measures provided.
It supports single user.	It supports multiple users.
Data fetching is slower for the large amount of data.	Data fetching is fast because of relational approach.
The data in a DBMS is subject to low security levels with regards to data manipulation.	There exists multiple levels of data security in a RDBMS.
Low software and hardware necessities.	Higher software and hardware necessities.
Examples: XML, Window Registry, Forxpro, dbaseIIIplus etc.	Examples: MySQL, PostgreSQL, SQL Server, Oracle, Microsoft Access etc.
Conclusion
Hence, it can be deduced that the administration system for databases is a software that oversees diverse operations like the technique of information input, the rapidity of information acquisition, and the capability to manage diverse categories of information encompassing structured, semi-structured, and unstructured.  It is beneficial when dealing with a limited quantity of data. Alternatively, a relational database pertains to a database that manages organised data. It comprises of distinct elements such as tuples (also known as rows) and schema (also known as tables). It stores data in a tabular form and establishes relationships between tables through key constraints. This type of database is beneficial when handling vast quantities of data.

What are primary and foreign keys?
https://www.reddit.com/r/explainlikeimfive/comments/127z2gm/eli5_can_someone_please_explain_to_me_the/

What is Indexing, Common indexing types. Explain with Example.
