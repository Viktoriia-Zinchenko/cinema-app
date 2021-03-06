![Logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQk1fDuOFhQGu9daSNCFSqSQoWhEUGGONSCw&usqp=CAU)

**Cinema App** is a simple web application that simulates the work of cinema service.
This project implements CRUD operations, authentication and registration.

The project is implemented in Java with SOLID principles & Dependency Injection,
has a 3-tier architecture.
***
# Functionality of Cinema App (endpoints) 🎬
___
* Register, login user
* Create, get all cinema halls
* Create, get all movies
* Create, update, delete, get all available movie session
* Complete order, get order history by user
* Get shopping cart bt user, add to cart
***
# Structure: 3-tier architecture 🎬
___
* DAO - Data Tier
* Service - Business Tier
* Controllers - Presentation Tier
***
# Technologies 🎬
___
* Java 11
* Tomcat 9.0.60
* Maven
* MySQL
* Hibernate
* Spring
***
# How to run a project 🎬
___
You need to install Ultimate IntelliJ IDEA, MySQL, TomСat webserver (version 9).
1. Configure TomСat.
2. In order to connect to the database it is necessary to add current data in the following fields
   URL, USERNAME, PASSWORD, JDBC_DRIVER in this file ```src/main/resources/db.properties```.
3. Start the project.
