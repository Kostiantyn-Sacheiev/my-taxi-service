# ﻿Taxi-Service

Welkome to my first application!

# Description:

This application can be useful if you have a purpose to administrate some little (or not very
*:)*
) service which has drivers who drive cars.

It supports authetication, and CRUD operation. Also it is connected to database.

The project implements a three-layer based architecture:
+ DAO - data access Tier
+ Service - business Tier
+ Controllers - presentation Tier

# Technologies
- JDK 11
- Java Servlet API 
- JSP
- JSTL 
- MySQL 
- JDBC
- Apache Tomcat 
- Apache Maven 

# Features:

- registration as a driver
- authentication as a driver
- create/update/remove a manufacturer
- create/update/remove a car
- create/update/remove a driver
- display a list of all manufacturers
- display a list of all cars
- display a list of all drivers
- display a list of all cars by current driver
- add a driver to the car

# DB structure:
![image](https://user-images.githubusercontent.com/110487085/202462080-1d7fb027-c073-4d37-aa8f-ad0db69ffdbc.png)

# How to use it

- Forked this project.
- If you don't have MySQL theт install it. 
- Сreate a schema by using the script from resources/init_db.sql.
- Set up and run Apache TomCat.
- Add your information to ConnectionUtil located in util (URL, login, password, JDBC driver) to be able to connect to your database.
- Configure Apache Tomcat in IDE
- Run the project using Tomcat local server

Thank you for your attention!
