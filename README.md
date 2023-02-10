
# ![diagram](taxi.png) Taxi-Service ![diagram](taxi.png)


# Project description
This is a simple project made to show my skills in Java, JDBC, WEB, OOP.
A simple web-application that supports authentication, registration and other CRUD operations
To use all features you need to create new driver and log in.

# Features:
- Registration like a driver
- Authentication like a driver
- Create/delete a car
- Create/delete a driver
- Create/delete a manufacturer
- Display list of all cars
- Display list of all drivers
- Display list of all manufacturers

# Technologies:
- Java 11 
- MySQL 
- JDBC 
- Servlet Api 
- JSP 
- JSTL 
- TomCat

# Project structure:

|       3-layer architecture       |
|:--------------------------------:|
| Controllers (Presentation layer) |
|                ↓↑                |
|   Services (Application layer)   |
|                ↓↑                |
|     DAO (Data access layer)      |

# Project launch instructions:

1. Clone the project from GitHub
2. Use /resources/init_db.sql to create a schema and tables
3. Configure /util/ConnectionUtil.java with your own URL, USERNAME and PASSWORD
4. Configure Tomcat server (it is recommended to use version 9.0.50)
   If you decide to install version 10 and above,
   you should use [a different dependency for servlets](https://mvnrepository.com/artifact/jakarta.servlet/jakarta.servlet-api/5.0.0)
   and [JSTL](https://mvnrepository.com/artifact/jakarta.servlet.jsp.jstl/jakarta.servlet.jsp.jstl-api/2.0.0) as well.
