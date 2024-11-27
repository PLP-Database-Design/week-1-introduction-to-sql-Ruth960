1.State and Explain the components of a DBMS(Database Management System)

key components  of DBMS:
a.Database Engine: Handles CRUD operations (Create, Read, Update, Delete), query processing, and transaction management.
b.Database Schema: Defines the structure of the database, including tables, relationships, and constraints.
c.Query Processor: Interprets and executes SQL queries through parsing, optimization, and execution.
d.Transaction Management: Ensures the integrity and consistency of the database through ACID properties (Atomicity, Consistency, Isolation, Durability).
e.Storage Manager: Manages physical data storage, memory buffers, and data retrieval.
f.Data Dictionary: Stores metadata about the database’s structure, such as table definitions and constraints.
g.User Interface (UI): Allows users to interact with the DBMS via a GUI, CLI, or API.
h.DBA Tools: Provide tools for database administration, performance monitoring, and security.
i.Backup and Recovery System: Ensures data can be backed up and restored after failures.

j.Security Management: Controls user access and ensures data protection through authentication, authorization, and encryption.

2.What is a relational database? Give 4 examples.

A relational database is a type of database that stores data in tables which are organized into rows and columns. Each table represents a different entity (such as customers, orders, or products), and relationships between data in different tables are established using keys (primary and foreign keys).
The relational model uses Structured Query Language (SQL) for querying and managing the data.
Examples of Relational Databases:
a.MySQL: A popular open-source relational database system widely used for web applications.
b.PostgreSQL: An open-source, advanced relational database known for its robustness and support for complex queries.
c.Oracle Database: A commercial relational database system used by large enterprises for handling vast amounts of data.
d.Microsoft SQL Server: A relational database management system developed by Microsoft, used for enterprise-level applications and business data management.

3.State and Explain three classifications of SQL?
Sql classified into three main categories based on its functionality:
1. Data Definition Language (DDL)
Explanation: DDL deals with the structure of the database, allowing users to define and modify database objects like tables, indexes, and schemas.
Key Commands:
CREATE: Creates a new database object (e.g., table, index).
ALTER: Modifies an existing database object.
DROP: Deletes a database object.
TRUNCATE: Removes all records from a table but does not remove the table itself.
2. Data Manipulation Language (DML)
Explanation: DML is used for managing and manipulating the data within database objects (e.g., inserting, updating, or deleting data).
Key Commands:
SELECT: Retrieves data from a database.
INSERT: Adds new records into a table.
UPDATE: Modifies existing data within a table.
DELETE: Removes records from a table.
3. Data Control Language (DCL)
Explanation: DCL is used for controlling access to data within the database, such as granting or revoking permissions.
Key Commands:
GRANT: Gives specific permissions (e.g., SELECT, INSERT) to users or roles.
REVOKE: Removes specific permissions from users or roles.
4.What is the difference between a Primary Key and a Foreign Key?
Differences
Feature	Primary Key	Foreign Key
Purpose	Uniquely identifies records within the same table.	Links records from one table to another.
Uniqueness	Must have unique values.	Can have duplicate values.
Nullability	Cannot contain NULL values.	Can contain NULL values.
Table	Used in a single table.	Used to reference a primary key in another table.

5.What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of the entities (objects or concepts) within a system and the relationships between them. It is commonly used in database design to model the structure of data and to illustrate how data is related within a database.
6.What are the advantages of relational databases?
·  Data Integrity: Constraints like primary and foreign keys ensure accurate and consistent data.
·  Flexibility and Scalability: They handle large datasets and complex queries efficiently.
·  SQL Support: Use of the standard SQL language makes data management easier and more compatible across systems.
·  Reduced Redundancy: Normalization minimizes data duplication and ensures efficient storage.
·  Data Management: Simple data manipulation with SQL commands makes it easy to add, update, or retrieve data.
·  Complex Queries: Ability to perform advanced queries using joins, aggregations, and subqueries.
·  Security: Provides robust security with user authentication and access control.
·  Transaction Management: Ensures reliable and consistent transactions with ACID properties.
·  Data Independence: Logical and physical data models are separate, allowing flexibility in data storage.
·  Wide Adoption: Relational databases are widely used, with strong community support.
7.State four types of data type used to store data in tables?
  Integer: Description: Stores whole numbers (positive, negative, or zero).
Example: INT, SMALLINT, BIGINT.
 Varchar (Variable-length character):  Description: Stores strings of variable length, such as names or addresses.
Example: VARCHAR(255), TEXT.
Date/Time:  Description: Stores dates, times, or both (useful for tracking events or transactions).
Example: DATE, TIME, DATETIME, TIMESTAMP.
 Decimal/Float:  Description: Stores numbers with decimal points (for precise calculations like currency or measurements).
Example: DECIMAL, FLOAT, NUMERIC.
8.What is the purpose of a database management system (DBMS)?
Data Storage: Organizes and stores data in structured formats (tables, rows, columns) for easy retrieval and management.
Data Retrieval: Allows users to query the database to retrieve specific information using languages like SQL.
Data Integrity: Ensures the accuracy and consistency of data through constraints, validation, and relationships between tables.
Security: Protects data by controlling access through authentication, authorization, and encryption.
Concurrency Control: Manages simultaneous data access by multiple users without conflicts or data corruption.
Backup and Recovery: Provides mechanisms for backing up data and restoring it after failures to prevent data loss.
Data Independence: Abstracts the physical storage of data from the logical view, enabling easier management and changes without affecting applications.
