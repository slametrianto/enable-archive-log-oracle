# enable-archive-log-oracle



Step 1: Connect With Container Database

C:\> SQLPLUS / AS SYSDBA

Step 2: Check the status of log mode

SQL> Shutdown immediate

Step 4: Mount The Database

SQL> STARTUP mount;

Step 5: Enable the Archive log mode.

SQL> ALTER DATABASE archivelog;

Step 6: Open The Database

SQL> ALTER DATABASE open;

Step 7: Check The Log mode

SQL> SELECT log_mode FROM v$database;
