<details>
<summary>What is DBMS ?</summary>
<br>
DBMS is a collection of programs that facilitates users to create and maintain a database. In other words, DBMS provides us an interface or tool for performing different operations such as the creation of a database, inserting data into it, deleting data from it, updating the data, etc. DBMS is a software in which data is stored in a more secure way as compared to the file-based system. Using DBMS, we can overcome many problems such as- data redundancy, data inconsistency, easy access, more organized and understandable, and so on. There is the name of some popular Database Management System- MySQL, Oracle, SQL Server, Amazon simple DB (Cloud-based), etc.
</details>

<details>
<summary>What is checkpoint in DBMS ?</summary>
<br>
The Checkpoint is a type of mechanism where all the previous logs are removed from the system and permanently stored in the storage disk.
There are two ways which can help the DBMS in recovering and maintaining the ACID properties, and they are- maintaining the log of each transaction and maintaining shadow pages. So, when it comes to log based recovery system, checkpoints come into existence. Checkpoints are those points to which the database engine can recover after a crash as a specified minimal point from where the transaction log record can be used to recover all the committed data up to the point of the crash.
</details>

<details>
<summary>When does checkpoint occur</summary>
<br>
A checkpoint is like a snapshot of the DBMS state. Using checkpoints, the DBMS can reduce the amount of work to be done during a restart in the event of subsequent crashes. Checkpoints are used for the recovery of the database after the system crash.
</details>

<details>
<summary>What are unary operators in relational algebra ?</summary>
<br>
PROJECTION and SELECTION are the unary operations in relational algebra. Unary operations are those operations which use single operands. Unary operations are SELECTION, PROJECTION, and RENAME.
</details>

<details>
<summary>What are types of Database Languages ?</summary>
<br>
-   **Data Definition Language (DDL)** e.g., CREATE, ALTER, DROP, TRUNCATE, RENAME, etc. All these commands are used for updating the data that?s why they are known as Data Definition Language.
-   **Data Manipulation Language (DML)** e.g., SELECT, UPDATE, INSERT, DELETE, etc. These commands are used for the manipulation of already updated data that's why they are the part of Data Manipulation Language.
-   **DATA Control Language (DCL)** e.g., GRANT and REVOKE. These commands are used for giving and removing the user access on the database. So, they are the part of Data Control Language.
-   **Transaction Control Language (TCL)** e.g., COMMIT, ROLLBACK, and SAVEPOINT. These are the commands used for managing transactions in the database. TCL is used for managing the changes made by DML.
</details>

<details>
<summary>What are the degree of a relation ?</summary>
<br>
The degree of relation is a number of attribute of its relation schema. A degree of relation is also known as Cardinality it is defined as the number of occurrence of one entity which is connected to the number of occurrence of other entity. There are three degree of relation they are one-to-one(1:1), one-to-many(1:M), many-to-one(M:M).
**One-To-One**: Here one record of any object can be related to one record of another object.
**One-To-Many (many-to-one)**: Here one record of any object can be related to many records of other object and vice versa.
**Many-to-many**: Here more than one records of an object can be related to n number of records of another object.
</details>

<details>
<summary>What is data abstraction and its types ?</summary>
<br>
Data abstraction in DBMS is a process of hiding irrelevant details from users. Because database systems are made of complex data structures so, it makes accessible the user interaction with the database.
Following are three levels of data abstraction:
**Physical level**: It is the lowest level of abstraction. It describes how data are stored.
**Logical level**: It is the next higher level of abstraction. It describes what data are stored in the database and what the relationship among those data is.
**View level**: It is the highest level of data abstraction. It describes only part of the entire database.
</details>

<details>
<summary>What is query optimization ?</summary>
<br>
The term query optimization specifies an efficient execution plan for evaluating a query that has the least estimated cost. The concept of query optimization came into the frame when there were a number of methods, and algorithms existed for the same task then the question arose that which one is more efficient and the process of determining the efficient way is known as query optimization.
There are many benefits of query optimization:
-   It reduces the time and space complexity.
-   More queries can be performed as due to optimization every query comparatively takes less time.
-   User satisfaction as it will provide output fast
</details>

<details>
<summary>What is normalization ?</summary>
<br>
Normalization is a process of analysing the given relation schemas according to their functional dependencies. It is used to minimize redundancy and also used to minimize insertion, deletion and update distractions. Normalization is considered as an essential process as it is used to avoid data redundancy, insertion anomaly, updation anomaly, deletion anomaly.
There most commonly used normal forms are:
-   First Normal Form(1NF)
-   Second Normal Form(2NF)
-   Third Normal Form(3NF)
-   Boyce & Codd Normal Form(BCNF)
</details>

<details>
<summary>What is denormalization ?</summary>
<br>
Denormalization is the process of boosting up database performance and adding of redundant data which helps to get rid of complex data. Denormalization is a part of database optimization technique. This process is used to avoid the use of complex and costly joins. Denormalization doesn't refer to the thought of not to normalize instead of that denormalization takes place after normalization. In this process, firstly the redundancy of the data will be removed using normalization process than through denormalization process we will add redundant data as per the requirement so that we can easily avoid the costly joins.
</details>

<details>
<summary>What is ER model ?</summary>
<br>
E-R model is a short name for the Entity-Relationship model. This model is based on the real world. It contains necessary objects (known as entities) and the relationship among these objects. Here the primary objects are the entity, attribute of that entity, relationship set, an attribute of that relationship set can be mapped in the form of E-R diagram.
In E-R diagram, entities are represented by rectangles, relationships are represented by diamonds, attributes are the characteristics of entities and represented by ellipses, and data flow is represented through a straight line.
</details>

<details>
<summary>What is entity, entity type, entity set, weak entity set, attribute</summary>
<br>
- The Entity is a set of attributes in a database. An entity can be a real-world object which physically exists in this world. All the entities have their attribute which in the real world considered as the characteristics of the object.
- An entity type is specified as a collection of entities, having the same attributes. Entity type typically corresponds to one or several related tables in the database. A characteristic or trait which defines or uniquely identifies the entity is called entity type.
- The entity set specifies the collection of all entities of a particular entity type in the database. An entity set is known as the set of all the entities which share the same properties.
- An entity set that doesn't have sufficient attributes to form a primary key is referred to as a weak entity set. The member of a weak entity set is known as a subordinate entity. Weak entity set does not have a primary key, but we need a mean to differentiate among all those entries in the entity set that depend on one particular strong entity set.
- An attribute refers to a database component. It is used to describe the property of an entity. An attribute can be defined as the characteristics of the entity. Entities can be uniquely identified using the attributes. Attributes represent the instances in the row of the database.
</details>

<details>
<summary>What is joins and its types</summary>
<br>
The Join operation is one of the most useful activities in relational algebra. It is most commonly used way to combine information from two or more relations. A Join is always performed on the basis of the same or related column. Most complex queries of SQL involve JOIN command.
There are following types of join:
-   Inner joins: Inner join is of 3 categories. They are:
    -   Theta join
    -   Natural join
    -   Equi join
-   Outer joins: Outer join have three types. They are:
    -   Left outer join
    -   Right outer join
    -   Full outer join
</details>

<details>
<summary>What is 1NF ?</summary>
<br>
**1NF** is the **First Normal Form**. It is the simplest type of normalization that you can implement in a database. The primary objectives of 1NF are to:
-   Every column must have atomic (single value)
-   To Remove duplicate columns from the same table
-   Create separate tables for each group of related data and identify each row with a unique column
</details>

<details>
<summary>What is 2NF ?</summary>
<br>
**2NF** is the **Second Normal Form**. A table is said to be 2NF if it follows the following conditions:
-   The table is in 1NF, i.e., firstly it is necessary that the table should follow the rules of 1NF.
-   Every non-prime attribute is fully functionally dependent on the primary key, i.e., every non-key attribute should be dependent on the primary key in such a way that if any key element is deleted, then even the non_key element will still be saved in the database.
</details>

<details>
<summary>What is 3NF ?</summary>
<br>
**3NF** stands for **Third Normal Form**. A database is called in 3NF if it satisfies the following conditions:
-   It is in second normal form.
-   There is no transitive functional dependency.
-   For example: X->Z
**Where:**  
X->Y  
Y does not -> X  
Y->Z so, X->Z
</details>

<details>
<summary>What is BCNF ?</summary>
<br>
**BCNF** stands for **Boyce-Codd Normal Form**. It is an advanced version of 3NF, so it is also referred to as 3.5NF. BCNF is stricter than 3NF.
A table complies with BCNF if it satisfies the following conditions:
-   It is in 3NF.
-   For every functional dependency X->Y, X should be the super key of the table. It merely means that X cannot be a non-prime attribute if Y is a prime attribute.
</details>

<details>
<summary>Explain ACID properties ?</summary>
<br>
ACID properties are some basic rules, which has to be satisfied by every transaction to preserve the integrity. These properties and rules are:
**ATOMICITY:** Atomicity is more generally known as ?all or nothing rule.' Which implies all are considered as one unit, and they either run to completion or not executed at all.
**CONSISTENCY:** This property refers to the uniformity of the data. Consistency implies that the database is consistent before and after the transaction.
**ISOLATION:** This property states that the number of the transaction can be executed concurrently without leading to the inconsistency of the database state.
**DURABILITY:** This property ensures that once the transaction is committed it will be stored in the non-volatile memory and system crash can also not affect it anymore.
</details>

<details>
<summary>Difference between DELETE and TRUNCATE command ?</summary>
<br>
**DELETE command**: DELETE command is used to delete rows from a table based on the condition that we provide in a WHERE clause.
-   DELETE command delete only those rows which are specified with the WHERE clause.
-   DELETE command can be rolled back.
-   DELETE command maintain a log, that's why it is slow.
-   DELETE use row lock while performing DELETE function.
**TRUNCATE command**: TRUNCATE command is used to remove all rows (complete data) from a table. It is similar to the DELETE command with no WHERE clause.
-   The TRUNCATE command removes all the rows from the table.
-   The TRUNCATE command cannot be rolled back.
-   The TRUNCATE command doesn't maintain a log. That's why it is fast.
-   TRUNCATE use table log while performing the TRUNCATE function.
</details>

<details>
<summary>What are 2 tier architecture and 3 tier architecture ?</summary>
<br>
The **2-Tier architecture** is the same as basic client-server. In the two-tier architecture, applications on the client end can directly communicate with the database at the server side.
The **3-Tier architecture** contains another layer between the client and server. Introduction of 3-tier architecture is for the ease of the users as it provides the GUI, which, make the system secure and much more accessible. In this architecture, the application on the client-end interacts with an application on the server which further communicates with the database system.
</details>

<details>
<summary>Describe types of keys ?</summary>
<br>
**There are following types of keys:**
**Primary key**: The Primary key is an attribute in a table that can uniquely identify each record in a table. It is compulsory for every table.
**Candidate key**: The Candidate key is an attribute or set of an attribute which can uniquely identify a tuple. The Primary key can be selected from these attributes.
**Super key**: The Super key is a set of attributes which can uniquely identify a tuple. Super key is a superset of the candidate key.
**Foreign key**: The Foreign key is a primary key from one table, which has a relationship with another table. It acts as a cross-reference between tables.
</details>



