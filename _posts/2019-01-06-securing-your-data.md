---
layout: post
title:  "Securing Your Data"
date:   2019-01-06
comments: true
categories: [rovergo, "getting started", security]
---

We take security very seriously at [RoverGo]({{site.rovergo_website}}). We encrypt all of your data, so you can rest assured your queries and connection information are safe. However, there are additional steps you can take to keep your data secure.

- Use a database or application role to limit what your SQL login can do. If your sql task only updates a few tables, you can limit the user you give RoverGo to only be allowed to update these tables. See [Security Center for SQL Server Database Engine and Azure SQL Database](https://docs.microsoft.com/en-us/sql/relational-databases/security/security-center-for-sql-server-database-engine-and-azure-sql-database) or [MySQL Reference Manual / Security](https://dev.mysql.com/doc/refman/8.0/en/security.html) for more information.
- Use a firewall to restrict which IP addresses can access your database. See [Azure SQL Database and SQL Data Warehouse firewall rules](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-firewall-configure) or [Azure Database for MySQL server firewall rules](https://docs.microsoft.com/en-us/azure/mysql/concepts-firewall-rules) for more information.
- Encrypt your database. Azure Databases for MySQL data is [always encrypted](https://docs.microsoft.com/en-us/azure/mysql/overview#secure-your-data), and you can use either [Always Encrypted](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/always-encrypted-database-engine) or [Transparent data encryption](https://docs.microsoft.com/en-us/azure/sql-database/transparent-data-encryption-azure-sql) for Azure SQL Databases.