# mysql

https://www.mysql.com/

https://cdn.mysql.com/archives/mysql-8.0/mysql-8.0.26-winx64.zip
https://cdn.mysql.com/archives/mysql-workbench/mysql-workbench-community-8.0.26-winx64.msi
https://cdn.mysql.com/archives/mysql-installer/mysql-installer-web-community-8.0.26.0.msi

```bash
mysql -?, --help

mysql -V, --version

mysqld --verbose --help

mysqld --initialize --console --datadir="C:/mysql-data"

mysqld --datadir="C:/mysql-data" &

mysql -u root -p
```

```mysql
help;
set password for 'root'@'localhost' = 'root';
alter user 'root'@'localhost' identified by 'root';
exit;
```

```mysql
show databases;
create database <db_database>;
drop database <db_database>;
use <db_database>;
select database();
system cd;
```