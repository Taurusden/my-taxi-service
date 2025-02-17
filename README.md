﻿
# TAXI SERVICE

### Project description

This project was created for people who need help in managing their taxi park.
It keeps all the information about cars, car manufacturers and drivers, who work in your company.

### Features

- driver registration;
- driver authentication;
- created, update and remove driver;
- created, update and remove manufacturer;
- created, update and remove car;
- display list of all manufacturer;
- display list of all drivers;
- display list of all cars;
- assign driver to car;
- give all info about driver by ID from DB;
- give all info about car by ID from DB;
- give all info about manufacturer by ID from DB.

### Project structure


- DAO - data access layer;
- Service - application logic layer;
- Controllers - presentation layer.

### Technologies

- Java 11
- Git
- Apache Maven
- Apache TomCat
- MySQL 8
- TomCat v.9.0.54
- JDBC
- Javax Servlet
- JSTL
- HTML/CSS

### Installation

(You need MySQL, TomCat v.9.0.54)

- Clone the project from GitHub;
- Use src/main/resources/init_db.sql for creating DB;
- Set connection with DB by editing src/main/java/taxi/util/ConnectionUtil.java
(you need fill next fields with own parametrs:
URL = adress your data base, for example : "jdbc:mysql://localhost:3306/taxi";
USERNAME = fill your login for access to data base;
PASSWORD = fill your password for access to data base;
JDBC_DRIVER = set driver for MySQL "com.mysql.cj.jdbc.Driver")
- Set TomCat;
- Run TomCat.
