# Persistence
Most web applications have to store something at some point in order to be useful. Lucee has multiple data storage options from SQL Databases, NoSQL, Files, and an Object Relational Mapper

##SQL Databases
Lucee supports persisting to many different datastores including all popular RDBMS (MySQL, SQL Server, PostgreSQL, Oracle) and NoSQL Datastores CouchDB, MongoDB and others.

##NoSQL Databases
The Lucee community has created extensions to operate with popular NoSQL databases. And any NoSQL database that provides a Java based connector can be used with Lucee. And NoSQL Databases that provide a SQL interface via a JDBC connector can be used with Lucee as a standard SQL datasource.

##Files
Lucee has native support for local file storage, RAM filesystem, FTP, & AWS s3, HTTP, and ZIP files

Source http://blog.getrailo.com/post.cfm/railo-tip-of-the-week-railo-resources

## ORM (Object Relational Mapping)

Lucee has built in support for modeling your domain objects with classes an Object Graph and persisting them to a SQL RDBMS. The ORM is best utilized with new developments, though it can be adapted to legacy SQL installations.
