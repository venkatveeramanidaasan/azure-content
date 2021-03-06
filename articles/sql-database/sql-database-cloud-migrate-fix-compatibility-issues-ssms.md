<properties
   pageTitle="Fix SQL Server database compatibility issues before migration to SQL Database"
   description="Microsoft Azure SQL Database, database migration, compatibility, SQL Azure Migration Wizard"
   services="sql-database"
   documentationCenter=""
   authors="carlrabeler"
   manager="jhubbard"
   editor=""/>

<tags
   ms.service="sql-database"
   ms.devlang="NA"
   ms.topic="article"
   ms.tgt_pltfrm="NA"
   ms.workload="data-management"
   ms.date="05/31/2016"
   ms.author="carlrab"/>

# Fix SQL Server database compatibility issues using SQL Server Management Studio before migration to SQL Database

> [AZURE.SELECTOR]
- Use [SQL Azure Migration Wizard](sql-database-cloud-migrate-fix-compatibility-issues.md)
- Use [SSDT](sql-database-cloud-migrate-fix-compatibility-issues-ssdt.md)
- Use [SSMS](sql-database-cloud-migrate-fix-compatibility-issues-ssms.md)

Advanced users can fix SQL Server database compatibility issues using SQL Server Management Studio before migration to Azure SQL Database.

## Using SQL Server Management Studio

Use SQL Server Management Studio to fix compatibility issues using various Transact-SQL commands, such as **ALTER DATABASE**. This method is primarily for advanced users that are comfortable working Transact-SQL on a live database. Otherwise, it is recommended that you use SSDT. 



## Next Steps

- [Newest version of SSDT](https://msdn.microsoft.com/library/mt204009.aspx)
- [Newest version of SQL Server Management Studio](https://msdn.microsoft.com/library/mt238290.aspx)
- [Migrate a compatible SQL Server database to SQL Database](sql-database-cloud-migrate.md#migrate-a-compatible-sql-server-database-to-sql-database)

## Learn More

- [SQL Database V12](sql-database-v12-whats-new.md)
- [Transact-SQL partially or unsupported functions](sql-database-transact-sql-information.md)
- [Migrate non-SQL Server databases using SQL Server Migration Assistant](http://blogs.msdn.com/b/ssma/)
