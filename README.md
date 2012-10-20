<<<<<<< HEAD
Subject: Steps to put the database in noarchivelog mode.



Host the oracle database environment

 [applmgrr@appstst db_1]$ pwd

/appl/atulorc11/product/11.1.0/db_1

[applmgrr@appstst db_1]$ . testdb_appstst.env 

SQL> connect /as sysdba

SQL> startup mount

SQL>alter database noarchivelog;

SQL>shutdown immediate

Cd /appl/atulorc11/product/11.1.0/db_1/appsutil/scripts/testdb_appstst

./ addbctl.sh start

./addlnctl.sh start testdb
=======
Project01
=========

Initial Project

Hello Everyone.....
>>>>>>> 45a6516c56dcb45b8ad98368f3db5f29f95c5f3e
