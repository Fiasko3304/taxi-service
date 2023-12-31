﻿# taxi-service
This is a small project I made to show my Java, OOP, JDBC, SOLID, Java Web, JSP, JSTL and SQL skills. 
# Available functionality:
- register as a driver;
- login as driver;
- create/update/delete a driver;
- display all drivers
- create/update/delete a car;
- display all cars;
- create/update/delete a manufacturer;
- display all manufacturers;
- add a driver to a car;
- display all cars for current login driver;
# Project Structure:
The project uses a multi-level architecture, namely:
- DAO - accepts requests from the service, passes them to the DB and executes all sql queries.
- Service - accepts requests from the controller, passes them to the DAO layer and performs all business logic.
- Controller - accepts requests from the user, passes them to the service layer and returns jsp pages in response.
# Technologies:
- Java 11
- JDBC
- JSP
- JSTL 1.2
- Maven 3.1.1
- MySQL 8.0.22
- Tomcat 9.0.50
- Servlet API 4.0.1
# Installation:
1. Fork this project to your repository
2. Press "Code" and choose HTTPS or SSH URL to clone the project
3. Install MySQL
4. Copy and run SQL script from resources/init_db.sql in order to create a schema and tables for the project
5. Configure Apache Tomcat version: 9.0.50
6. Configure /util/ConnectionUtil.java with your own URL, username, password and JDBC driver
7. Run the project
