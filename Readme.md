
# Alcaline - Spring Boot Backend

This project contains the backend implementation for the Alcaline application using Spring Boot.

======================================================================================================================================================================================

## Prerequisites

- Java Development Kit (JDK) - version 8 or higher
- Maven
- Your preferred IDE (IntelliJ IDEA, Eclipse, etc.)
- Database (MySQL, MySql Workbbench)
- set the necessary dependencies (like Spring Web, Spring Data JPA, etc.), and download the project.


## Project Structure

alcaline/
├── src/
│   ├── main/
│   │   ├── java/               # Java source files
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── alcaline/
│   │   │               ├── controller/     # REST API controllers
│   │   │               ├── entity/         # Entity classes
│   │   │               ├── repository/     # JPA repositories
│   │   │               ├── service/        # Service classes
│   │   │               └── AlcalineApplication.java  # Main Spring Boot application class
│   └── resources/          # Configuration files, properties, static resources, etc.
└── pom.xml                 # Maven project configuration file

======================================================================================================================================================================================


### Configuration:

Update the database configuration in folder src/main/resources/application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

Modify other properties like server port as needed.	

======================================================================================================================================================================================

### Maven Clean and Install:

In the terminal, navigate to the root folder of your project (alcaline) and execute:
mvn clean install

This command will clean the project, download dependencies, and build the project.

===========================================================================================================

### Database Setup:

We've integrated Hibernate for our database in the Spring Boot application. 
Ensure that the Hibernate configuration is correctly set in the application.properties file located at src/main/resources/application.properties

spring.jpa.hibernate.ddl-auto=update  

### DataBase Population :- 

Files can be found under the folder Data Population Queries in the submission zip.  

      Importing CSV File:

	Open MySQL Workbench: Launch MySQL Workbench and connect to your MySQL server.

	Select Database: Choose the database where you want to import the CSV file.

	Rightclick on table and select Table data Import Wizard (we have provide individual table csv file for table data).	

	Select Source: Choose 'Import from Self-Contained File'.

	Choose File: Click on the folder icon and navigate to the CSV file you want to import.

	Set Options: Define import options like the target schema, tables, etc., according to your needs.

	Start Import: Click 'Start Import' to initiate the CSV file import process.

===============================================================================================================================

### Run the Application:

Run the AlcalineApplication.java file (or the class containing the @SpringBootApplication annotation) as a Java application in your IDE.


### Lines of code (alcaline)

Java Files - 1833


======================================================================================================================================================================================


# Insurance React Frontend

This project contains the frontend codebase for the Insurance application.

## Prerequisites
Make sure you have the following installed before proceeding:

- Node.js - Download & Install Node.js
- npm (Node Package Manager) - comes with Node.js installation

=======================================================================

# Getting Started

To get a copy of this project up and running on your local machine, follow these steps:

First you have to navigate to a our folder "insurance" (Note: This folder contains -> src, componenet, Services, Redux, Images, CSS, few js files and package.json )

if not you can navigate using command:-
- cd Insurance


# Next Install all the dependencies 

To install run below command:- 
- npm install



(Note:- Before starting the project please make sure nothing is running on port 3000, localhost:3000)
(Note:- Make sure Backend server is Up and run before starting frontend)

# Now you have to run project:- 

- npm start


======================================================================================================================================================================================


Important aspect of the project :-



1. How many total lines of code written?

   Java Files - 1833
   JS (Java Script) - 7298 lines of code 
   CSS - 2263 

   Total :- 11,394 lines of code 


2. What are the features  (including required assignments features) implemented and functional in your project?

     2.1 User Account/Profile/Transaction management & MySQL

     2.2 Recommender

     2.3 Analytics & Visual Reports                                

     2.4 Google MAPS 

 
3. What are the Assignments features that are NOT implemented?

     - Reviews & Trending & MongoD

     - Auto-Complete Search feature

     - Knowledge Graph Searches



4. What are the Assignments features that are attempted but NOT functional?

    NIL



