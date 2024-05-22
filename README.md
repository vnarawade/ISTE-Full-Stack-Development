
#  Beauty-Products Business Management Web Application : <br>



Technologies used: 
1. Spring Boot ->Backend framework for building Java-based web applications.
2. Thymeleaf  ->Server-side Java template engine for dynamic HTML generation.
3. MySQL(Spring JPA)      -> Relational database management system for data storage.
4. IDE/Tool    -> Spring Tool Suite (Eclipse)
5. Project Management --> Maven
6. Server         --> Embedded Tomcat Server

Features:
1. Customer Management: Easily add, update, and delete customer information.
2. Inventory Management: Keep track of your inventory items, including stock levels and pricing.
3. User Authentication: Secure login and authentication for admin and staff members.
4. Role-Based Access Control: Define roles and permissions for different user types.
5. Thymeleaf Templates: Utilizes Thymeleaf for dynamic HTML templates.
6. Database Integration: Integrated with MySQL for data storage.
User Modules:
1. Administrator
2. Ordinary user

Functional Module: 
1. User Authentication --> Login, Register
2. Product category      --> Add category, view categories
3. Product	        --> Add product, view products, search products by Category

Installation:
1. Clone the repository : $ git clone 
https://github.com/sujataoak799/ISTE-JFSD-Mini-Project or Download the zip
2. Import the project inside Eclipse :
o Open Eclipse > file > import > maven > existing project > browse > finish .
3. Make sure you are in the Spring_Boot_Project-master  directory.
4. Configure the database connection in application.properties (check the Database section for more information).
5. Run the project (by running main method is SsBeautyProductsApplication.java) OR right clink on the project > Run As > Spring Boot App.
6. Open http://localhost:8080/home in any browser.
7. Now your tables will be created in the databse.
* You have to add one admin data manually to login as admin, So add one admin data.

Database:

MySQL can be used as the database for this project. The database connection can be configured in the application.properties file, with the appropriate values for the following properties:

spring.datasource.name=beautyproject
spring.datasource.url=jdbc:mysql://localhost:3306/beautyproject
spring.datasource.password=Rsenthil_1976
spring.datasource.username=root
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.hibernate.ddl-auto=update
spring.jpa.open-in-view=false

