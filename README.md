# 3-Laravel-9-With-Various-DataBases

Create new laravel 9 project and check it with various databases(MySQL, MariaDB, PostgreSQL, SQLite, SQL Server ) with Laravel.



### Data Bases

#### 1) MySQL

If we want to connect MySQL DataBase with laravel 9, we must edit these variables in .env file of that laravel project similar to our MySQL configurations.
**If password not set to MySQL Database, then leave it as empty** 
 
```bash
DB_CONNECTION=mysql 
DB_HOST=127.0.0.1 
DB_PORT=3306 
DB_DATABASE=db 
DB_USERNAME=root 
DB_PASSWORD=******

```
#### 2) MariaDB

MariaDB is an open-source fork of MySQL created in 2009. MariaDB is a backward-compatible improved version of MySQL. It comes with various inbuilt capable features and many security and execution improvements missing in MySQL. MariaDB supports the same features that MySQL does but offers additional ones too.

If we want to connect MariaDB DataBase with laravel 9, we must edit these variables in .env file of that laravel project similar to our MariaDB configurations.
**If password not set to MariaDB Database, then leave it as empty.** 

MySQL and MariaDB are pretty much similar in .env variables.
 
```bash
DB_CONNECTION=mysql 
DB_HOST=127.0.0.1 
DB_PORT=3306 
DB_DATABASE=db 
DB_USERNAME=root 
DB_PASSWORD=******

```
#### 3) PostgreSQL

If we want to connect PostgreSQL DataBase with laravel 9, we must edit these variables in .env file of that laravel project similar to our PostgreSQL configurations.
 
```bash
DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=2_laravel_9_project_sample
DB_USERNAME=postgres
DB_PASSWORD=

```
#### 4) SQLite

If we want to connect SQLite DataBase with laravel 9, we must edit these variables in .env file of that laravel project similar to our SQLite configurations.
 
```bash
DB_CONNECTION=sqlite
DB_HOST=127.0.0.1
DB_PORT=3306

```
 create our database inside your Laravel 9 directory project and navigate to the following path: **project_folder/database** then create a file named **database.sqlite**.

we can use any .sqlite extentions to view tables of project.

** database.sqlite file only contain one DB of that project**

#### 5) SQL Server

If we want to connect SQL Server DataBase with laravel 9, we must edit these variables in .env file of that laravel project similar to our SQL Server configurations.
 
```bash
DB_CONNECTION=sqlsrv
DB_HOST=GERI\SQLEXPRESS
DB_PORT=
DB_DATABASE=2_laravel_9_project_sample
DB_USERNAME=
DB_PASSWORD=

```

## 🛠 Skills accomplished during this project

**Set up all above database management systems on developemt environment**\
    - **MySQL**\
    - **MariaDB**\
    - **PostgreSQL**\
    - **SQLite**\
    - **SQL Server**


**Connect all above DBMS with laravel 9**\
    - .env DB configration and migrate tables and data to above DBMS\

**Advantages and disadvantages of all bove DBMS**\
    - comparing each other and able to select which is suitable based on kind of project



## Author

- [@Geriththanan](https://github.com/Geriththanan)
