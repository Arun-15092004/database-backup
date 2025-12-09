Project Name: SQL Server + Application Backup Tool

Step 1 – Create DB Backup

Enter Server Name → Database → Local Folder → Backup Type → Click Create Local Backup

SQL Server generates a .bak file on your local machine.

Step 2 – Move DB Backup to Network Share

Enter network path → username → password → Click Move Backup to Network

Backup file is moved to the network server.

Step 3 – Backup the Application Files

Enter source project path → network credentials → destination path
This module is separate from the SQL backup.
It copies your entire application folder (files, images, .dlls, configs, etc.).

Uses:
Backup website/application before deployment
Backup project folders to remote server
Keep daily snapshots of app files

Click Copy Files

All app files are copied to the network backup folder.

Step 4 – Final Result

On your network server, you will have:

\DB_App_Backup_Tool
      ├── SQL Backups (.bak)
      ├── Application Files
      ├── WebApplication3\ (all code)
      
      technology used:
1.ASP.NET Web Forms
2.C# (Code-Behind)
3.SQL Server
4.ADO.NET
5.System.IO (File Operations)
6.Windows Network Share (UNC Paths)
7.HTML
8.CSS
9.Bootstrap
10.JavaScript / jQuery
11.IIS / Localhost Hosting
