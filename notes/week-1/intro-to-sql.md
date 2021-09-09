# SQL
SQL, or Structured Query Language, is a scripting language used to manipulate relational databases, commonly referred to as SQL databases. In the strictest sense SQL instructs a relational database management system in a similar way to how Java instructs the compiler and JS instructs the interpreter.

## SQL Sublanguages
The types of SQL commands used to query and manipulate data within a database can be categorized into 5 sub-languages (or dialects). We will be primarily interested in the first 3 seen below, DDL, DML, and DQL. 

1. **DDL Data Definition Language:** Statements used to create tables and databases as well as defined properties.
    * `CREATE`, `ALTER`, `DROP`, `TRUNCATE`
2. **DML (Data Manipulation Language):** Statements used to insert or remove data from tables.
    * `INSERT`, `UPDATE`, `DELETE`
3. **DQL (Data Query Language):** Statements used to query data from a table.
    * `SELECT`
4. **DCL (Data Control Language):** Statements used to control who can access data.
    * `GRANT`, `REVOKE`
5. **TCL (Transaction Control Language):** Statements used to commit and restore data through transaction.  Transactions group a set of tasks into a single execution unit.
    * `COMMIT`, `ROLLBACK`, `SAVEPOINT`