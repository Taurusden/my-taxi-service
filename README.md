
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
- MySQL
- JDBC
- Javax Servlet
- JSTL
- HTML/CSS

### Installation

(You need MySQL, TomCat v.9.0.54)

- Clone the project from GitHub;
- Use init_db.sql for creating DB;
- Set connection with DB by editing ConnectionUtil;
- Set TomCat;
- Run TomCat.
