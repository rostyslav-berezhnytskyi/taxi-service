![taxi-5693219_960_720](https://user-images.githubusercontent.com/108344763/192264893-1f2a8e2b-ddd2-4646-a124-87ef4a345164.png)
## 📖 Description
This application is my implementation of a simplified version of the taxi web service.

## 📋 Project structure
**The project has an N-Tier Architecture**
- Controller layer - responsible for enabling the user to work with the application through a web browser.
- Service layer - responsible for the implementation of the entire business logic of the application.
- DAO layer - responsible for the interaction of the application with the database.
- DB - the database is based on the MySQL server.
- DB representation:


![car_diagram_db_2_4f50942103](https://user-images.githubusercontent.com/108344763/192262186-ce8b2661-e8de-4093-bd29-7befe1784f5b.png)



## 🎯 Features
- authentication
- create, update, delete manufacturers, cars, drivers
- add driver to car / remove driver from car
- display list of all manufacturers, cars, drivers

## 🖥️ Technologies
- Java 11
- JDBC
- JSP
- MySQL
- Maven
- Tomcat

## 🚀 Quickstart
1. Fork this repository
2. Copy link of project
3. Create new project from Version Control
4. Edit ConnectionUtil.class - set the necessary parameters
``` java
    private static final String URL = "YOUR DATABASE URL";
    private static final String USERNAME = "YOUR USERNAME";
    private static final String PASSWORD = "YOUR PASSWORD";
    private static final String JDBC_DRIVER = "YOUR DRIVER";
```
5. Create the necessary tables in your database using the file init_db.sql
6. Install [Tomcat] (https://tomcat.apache.org/download-90.cgi)
7. Add Tomcat server to configuration and Fix it.
8. Run project
