## Conexión mediante JDBC, Hibernate a base de datos PostgreSQL.
---------------------------------------------------------------

## Hibernate Properties
-----------------------
Following is the list of important properties, you will be required to configure for a databases in a standalone situation −

Sr.No. 	Properties & Description
1. hibernate.dialect
This property makes Hibernate generate the appropriate SQL for the chosen database.

2. hibernate.connection.driver_class
The JDBC driver class.

3. hibernate.connection.url
The JDBC URL to the database instance.

4. hibernate.connection.username
The database username.

5. hibernate.connection.password
The database password.

6. hibernate.connection.pool_size
Limits the number of connections waiting in the Hibernate database connection pool.

7. hibernate.connection.autocommit
Allows autocommit mode to be used for the JDBC connection.

> If you are using a database along with an application server and JNDI, then you would have to configure the following properties −

Sr.No. 	Properties & Description
1. hibernate.connection.datasource
The JNDI name defined in the application server context, which you are using for the application.

2. hibernate.jndi.class
The InitialContext class for JNDI.

3. hibernate.jndi.<JNDIpropertyname>
Passes any JNDI property you like to the JNDI InitialContext.

4. hibernate.jndi.url
Provides the URL for JNDI.

5. hibernate.connection.username
The database username.

6. hibernate.connection.password
The database password.

A continuación se muestra la lista de varios tipos de propiedad de dialecto de bases de datos importantes:

No Señor. 	Propiedad de base de datos y dialecto
1. DB2
org.hibernate.dialect.DB2Dialect

2. 	HSQLDB
org.hibernate.dialect.HSQLDialect

3. 	SQL hipersónico
org.hibernate.dialect.HSQLDialect

4. 	informax
org.hibernate.dialect.InformixDialect

5. 	Ingre
org.hibernate.dialect.IngresDialect

6. 	Interbase
org.hibernate.dialect.InterbaseDialect

7. 	Microsoft SQL Server 2000
org.hibernate.dialect.SQLServerDialect

8. 	Servidor Microsoft SQL 2005
org.hibernate.dialect.SQLServer2005Dialect

9. 	Servidor Microsoft SQL 2008
org.hibernate.dialect.SQLServer2008Dialect

10. 	mysql
org.hibernate.dialect.MySQLDialect

11. 	Oracle (cualquier versión)
org.hibernate.dialect.OracleDialect

12. 	oráculo 11g
org.hibernate.dialect.Oracle10gDialect

13. 	Oráculo 10g
org.hibernate.dialect.Oracle10gDialect

14. 	oráculo 9i
org.hibernate.dialect.Oracle9iDialect

15. PostgreSQL
org.hibernate.dialect.PostgreSQLDialect

16. Progreso
org.hibernate.dialect.ProgressDialect

17. 	Base de datos SAP
org.hibernate.dialect.SAPDBDialect

18. Sybase
org.hibernate.dialect.SybaseDialect

19. 	Sybase en cualquier lugar
org.hibernate.dialect.SybaseAnywhereDialect

