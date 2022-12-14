# 🚕<span style="color:yellow">Taxi-service</span> 🚖
## :page_with_curl: Project description:
>This is a simple web application, as a learning project, realized in Java, based on SOLID principles, performs CRUD, authentication and registration operations. The main purpose of this application is to keep records of taxi service drivers and cars
_____
## :pushpin: Project structure:
> - N-Tier Architecture was used
> - DAO - Data access Tier (CRUD methods)
> - Service - Business Logic Tier
> - Controller - Presentation Tier
___
## :collision: Features:
>* registration a new driver
>* login / logout
>* create, update and remove all models
>* display list of all manufacturers, cars, drivers
___
## :wrench: Technologies:
>* MySQL 8.0.31
>* JDBC
>* Java Servlet API  4.0.1
>*  Java 11
>*  Maven 3
>*  Tomcat 8.5.83
>*  JSP 2.3.3
____
# <span >DataBase structure</span> 



![diagram](img/taxi_models_diagram.jpeg)
## :newspaper: How to launch the project on your PC:
* Fork this repo
* Create schema and all tables using the file `init_db.sql`
* Config ConnectionUtil.class
```java
  private static final String URL = "URL";
  private static final String USERNAME = "USERNAME";
  private static final String PASSWORD = "PASSWORD";
  private static final String JDBC_DRIVER = "JDBC_DRIVER";
```
* Install [Tomcat](https://tomcat.apache.org/download-90.cgi)
* Add Tomcat server to configuration
* Run project
