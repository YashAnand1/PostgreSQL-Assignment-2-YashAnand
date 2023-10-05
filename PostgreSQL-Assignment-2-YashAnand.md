What is RDBMS?

In an RDBMS or Relational Database Management System, the data is organised into tables with rows and columns - like it is done in a spreadsheet. The data entered in a row of the table would be associated with its respective column's header, making the data more structured and tidy. The main component of an RDBMS therefore consists of its capability of inputting data as tables and also allowing data interaction and management based on the relationship between the tables. 

In order to better explain this, let's take an example of a 'Soft-Drink refrigerator' as the one that has been displayed below.

Lets assume that the manager of the store that this fridge is set up in, wishes to efficiently manage information related to the various soft drinks such as:
- Name of all the soft-drink brands
- Details related to supplier of the soft-drinks

In order to do so, he could utilise an RDBMS to help him store and manage data in the form of various tables. This could be done by creating one table called "Brand_Names" and another called "Supplier_Details", and populating the related data into these tables. However, in order to check which supplier is in charge of supplying a specific soft-drink, a relation could be easily formed between the 2 tables for relating different brands with their suppliers, in the following way:

<will be attaching video or screenshot or plantuml diagram>

--------

What is ACID, Explain with example.

ACID Compliance in the context of databases stands for Atomicity, Consistency, Isolation and Durability. Atomicity: Think of atomicity as a magic wand. When you use it, all the steps to make the cake happen together, like magic. If anything goes wrong, the magic wand waves and everything goes back to how it was before you started. So, you either have a perfect cake, or you don't have a cake at all.

Consistency: This is like a cake recipe that never changes. When you follow the recipe, you expect your cake to taste the same every time. ACID ensures that your cake recipe is consistent, so you don't accidentally add chili powder instead of sugar.

Isolation: Imagine you're baking your cake in a busy kitchen with other people. Isolation makes sure that no one messes with your ingredients or your cake while you're baking. Your cake stays safe and separate from others' cooking adventures.

Durability: Once you've baked your cake and it's perfect, durability means it's safe for the long haul. Even if your kitchen has a power outage or a tornado, your cake will stay exactly as you left it—delicious and ready to eat.

So, in simple terms, ACID is like a magical recipe for making cakes (or any important task), where everything happens together (atomicity), the taste is always consistent (consistency), your cake stays safe from others' meddling (isolation), and it lasts forever, no matter what (durability). It helps keep important things in your database just right, like a perfectly baked cake!

Explain RDBMS vs DBMS.

Why DBMS Required?
Database management system, as the name suggest, is a management system which is used to manage the entire flow of data, i.e, insertion of data or the retrieval of data, how the data is inserted into the database or how fast the data should be retrieved, so DBMS takes care of all these features, as it maintains the uniformity of the database as well does the faster insertions as well as retrievals.

Why RDBMS Required?
RDBMS on the other hand is a type of DBMS, as the name suggest it deals with relations as well as various key constraints. So here we have tables which is called as schema and we have rows which are called as tuples. It also aids in the reduction of data redundancy and the preservation of database integrity.

Relational Database Management System is an advanced version of a DBMS. 
 

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
