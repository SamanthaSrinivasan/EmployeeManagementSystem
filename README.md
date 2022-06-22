# Employee Management System

	- Employee info: empid,firstname,lastname,emailid,department,location and phonenum entered in web app will be stored database
	- User friendly application
	- Reduces errors caused from manual system
	- Easy to take actions like Update and Delete record of employee

## Technologies Used : 
	
  - Spring Data JPA :: To develop DAO Layer 
      
  - Springboot Framework :: To develop web app and maven for dependency management 

  - Core Java 

  - MySql 

  - Html,Thymeleaf,Css with Bootstrap,Javascript :: To develop view layer

	
All these technologies put together helps in creating a full-fledged highly responsive application.


## - EMS Architecture :

	Frontend - Browser - thymeleaf template engine to develop view layer and to make website responsive - to handle http request
  
	Backend - 3 layer architecture 
                  - Controller (handle methods like get,post)
                  - Service (logics)
                  - Repository (connect with sql,crud for emp)

## - EMS Features :
    Registration
    Login
    Add Employee
    Update Employee
    List Employee   
    Sort Employee
    Delete Employee	
    Pagination
    Logout
    
  
  
## - IDE's

### SpringToolSuite4 Packages : 

> EmployeeManagementWebAppApplication - Main entry point class of springboot project

> Config - Spring Security Configurations for authentication 

> Controller -  Method handlers for displaying  in the view layer

> Dto - Data transfer obj : Instead of transferring single piece of info, use dto to pass bulk info from server to client and vice versa

> Model - All domain model 

> Repository - Repository Interface extends jpaRepository which implements all CRUD operations on Employee and User entities

> Service - For all service classes and its implemented methods

> By default spring boot will access thymeleaf from templates folder :
  index.html,login.html,newemployee.html,registration.html,updateemployee.html

> application.properties  - Configure MySql Database 

> pom.xml - Maven dependencies,pulgins,build related things



### mySql Workbench : 

> create database demo;
> use demo ;

    - web app : register
    - sql : select * from user
    > password - encrypted using web security support using inbuilt BCryptPasswordEncoder which uses hashing function with Spring Security Configurations for authentication 

    - web app : Add employee
    - sql : select * from employees
    > ddl - auto update command is been given already in application.properties in sts so as the records are been entered, it will be updated parallely


## Glossary :

> Spring Data Jpa 
  
    - Java Persistant API
    - Easy implementation of jpa based repositories
    - Access,Manage,Persist data between java obj and relational database
    - Bridge between obj oriented domain models and database               

> DAO Layer 
  
    - Data Access Obj 
    - Encapsulation 
    - Data operations without exposing details to database

> Springboot Framework 
 
    - Open source application framework to support Java Enterprise Edition frameworks 
    - Spring helps to create high performing applications using pojo
    
> Bootstrap 

    - Free and open source framework for front end development for creation of websites and web apps 
    - Built on html,css,js to facilitate developemnt of responsive apps 
    - Design template
    
> Hashing Function 

    - plain text-- hashing algo-- hash value 
    - SHA1 - converts strings of different length into fixed length strings called hash values 
    - converting given value of key into another value -- encrypt and decrypt
    
> Maven 

    - Written in java to build projects based on Pom 
    - Used by java developers for delivering reports,check,build and test automation setups
  
> http request 

    - Made by client to a named host which is located in server 
    - To make request as client uses url to gain access in the server

> Web-app - Runs on a web browser instead of software which requires to download and run on the os 

> Java 8 - forEach() for iterable interface

> mySql - Structured Query Lang - access,manipulate,retrieve data from database 

> DDL Cmds - create,alter,drop,rename,truncate,comment

> DML Cmds - select,insert,update,delete,merge

> Database - Organized collection of data stored for access,management and updating info
 
> Html - Standard markup language for docs designed to be displayed in web browser

> Thymeleaf - Template engine for processing and creating html,css,js

> Dependency Management - Declaration and Configurations 

> CRUD - Create Read Update Delete

> Inline css - css into html instead of external css

> Alert - Feedback msgs to user actions

> pulgins - Package of executable jar or war archieves

> jar - Compiled java classes from the project

> war - Distributes a collection of jar files 

> build - Order to be executed

> get - Requesting data from server- read data

> post - Data insertion and updation -  send data




