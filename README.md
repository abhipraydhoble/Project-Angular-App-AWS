# Installing MariaDB, Setting Password, and Importing Database on Ubuntu Linux

This guide will walk you through the process of installing MariaDB on Ubuntu Linux, setting a password, and importing a database from a SQL file. MariaDB is a popular open-source relational database management system, and it's commonly used in web development environments.
##  Create database in instance

![db](https://github.com/abhipraydhoble/Project-Angular-App/assets/122669982/8d992b33-4a08-4a68-95ab-1021c1111791)

## Setup MariaDB and Import MySQL

Before installing any new software, it's essential to update the package lists to ensure you're getting the latest versions available.

```bash
sudo apt update
sudo apt install mariadb-server
sudo systemctl start mariadb
sudo systemctl enable mariadb


```
## Login Into Database
````
sudo mysql -h database-1.cxqukacgq5pj.us-east-1.rds.amazonaws.com -u Angular-db -pPasswd123$
```sql
CREATE DATABASE springbackend;

```

### Import Database from SQL File
```bash
sudo mysql -h database-1.cxqukacgq5pj.us-east-1.rds.amazonaws.com -u Angular-db -pPasswd123$ springbackend < springbackend.sql
```
```bash
sudo mysql -h database-1.cxqukacgq5pj.us-east-1.rds.amazonaws.com -u Angular-db -pPasswd123$
```
```sql
show databases;
show tables;
select * from tbl_workers;
```
