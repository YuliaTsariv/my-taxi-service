# 🚕<span style="color:yellow">Taxi-service</span> 🚖
## :page_with_curl: Project description:
>This is a simple web application, as a learning project, realized in Java, based on SOLID principles, performs CRUD, authentication and registration operations. The main purpose of this application is to keep records of taxi service drivers and cars
_____
## :pushpin: Project structure:
> - This is an N-Tier Architecture
> - DAO - Data access Tier (CRUD methods)
> - Service - Business Tier
> - Controller - Presentation Tier
___
## :collision: Features:
>* registration a new driver
>* login / logout
>* create, update and remove all models
>* display list of all manufacturers, cars, drivers
___
## :wrench: Technologies:
>* MySQL
>* JDBC
>*  Java 11
>*  Maven
>*  Tomcat
>*  JSP
____
## :newspaper: How to launch the project on your PC:
* Fork this repo
  `git clone <your link>`
* Create schema and all tables using the file init_db.sql
* Config ConnectionUtil.class
* 
```java
private static final String URL = "URL";
  private static final String USERNAME = "USERNAME";
  private static final String PASSWORD = "PASSWORD";
  private static final String JDBC_DRIVER = "JDBC_DRIVER";
```
* Install [Tomcat](https://tomcat.apache.org/download-90.cgi)
* Add Tomcat server to configuration
* Run project
