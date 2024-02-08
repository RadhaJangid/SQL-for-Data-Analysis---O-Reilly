# What Is SQL?
SQL is the language used to communicate with databases. The acronym stands for Structured Query Language and is pronounced either like “sequel” or by saying each letter, as in “ess cue el.” It isn’t a general purpose language in the way that C or Python are.SQL became an International Organization for Standards (ISO) standard in 1987 and an American National Standards Institute (ANSI) standard in 1986.

SQL is used to access, manipulate, and retrieve data from objects in a database.
Databases can have one or more schemas, which provide the organization and structure and contain other objects. Within a schema, the objects most commonly used in data analysis are tables, views, and functions. Tables contain fields, which hold the data. Tables may have one or more indexes; an index is a special kind of data structure that allows data to be retrieved more efficiently. Indexes are usually defined by a database administrator. Views are essentially stored queries that can be referenced in the same way as a table. Functions allow commonly used sets of calculations or procedures to be stored and easily referenced in queries. They are usually created by a database administrator, or DBA. 

To communicate with databases, SQL has four sublanguages -
DQL, or data query language, It’s used for querying data. DQL commands include SELECT. SQL queries generally cannot query across databases, but in some cases clever network settings or additional software can be used to retrieve data from multiple sources, even databases of different types.

DDL, or data definition language, is used to create and modify tables, views, users, and other objects in the database. It affects the structure but not the contents. There are three common commands: CREATE, ALTER, and DROP. CREATE is used to make new objects. ALTER changes the structure of an object, such as by adding a column to a table. DROP deletes the entire object and its structure.

DCL, or data control language, is used for access control. Commands include GRANT and REVOKE, which give permission and remove permission, respectively.

DML, or data manipulation language, is used to act on the data itself. The commands are INSERT, UPDATE, and DELETE. INSERT adds new records and is essentially the “load” step in extract, transform, load (ETL). UPDATE changes values in a field, and DELETE removes rows.

Variations in SQL from database to database are often termed dialects.
