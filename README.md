# TAXI SERVICE

This project demonstrates my skills in designing a 3-tier web application using servlets. The application rather superficially solves the problems of the business logic of the taxi service.
This application has several possibilities, namely:
* User authorization and registration (Taxi driver)
* Display of all drivers who are registered in the system
* Display of all cars, their manufacturers, and drivers that are assigned to these cars
* Adding new cars, manufacturers
* Assign a specific car to the driver
* As well as selective removal of all the above

### Implementation details and technologies
#### Project based on 3-layer architecture:
* Presentation layer (controllers)\
* Application layer (services)\
* Data access layer (DAO)

#### Technologies
* Apache Tomcat (9.0.50)
* Servlet
* JDBC
* MySQL
* JSTL
* HTML, CSS
* JSP
* Maven

#### Setup
1. Install and configure MySQL & MySQL Workbench
2. Install and configure Tomcat
3. In MySQL Workbench, execute the script from resources/init_db.sql
4. Link the database to the application: in /util/ConnectionUtil.java, change the USER, PASSWORD, and URL constants to the ones you used when configuring MySQL. JDBC_DRIVER change if you are using another DBMS.
5. Specify your absolute path to the file where you want to write logs in the file /resources/log4j2.xml instead of "YOUR ABSOLUTE PATH TO THE LOG FILE".
6. After that you can run the application ;)