# SQL Server AdventureWorks sample database

## Restore AdventureWorks2017.bak
  - Open SQL Server Management Studio and connect to the target SQL Server instance.
  - Right-click on the Databases node, and select Restore Database.
  - Select Device and click the ellipses (...)
  - In the dialog “*Select backup devices*”, click Add, navigate to the database backup in the filesystem of the server, and select the backup. Click OK.
    *Directory must have been granted read rights to NT Service\MSSQLSERVER*!
  - If needed, change the target location for the data and log files, in the Files pane. Note that it is best practice to place data and log files on different drives.
  - Click OK. This will initiate the database restore. After it completes, you will have the AdventureWorks database installed on your SQL Server instance.

## Links

https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15
