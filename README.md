National Geographic Articles Collection - Spring Boot Backend
Overview
This project is a Spring Boot backend application designed to manage and display a collection of National Geographic articles. The application receives data from a MySQL server and is built using Object-Oriented Programming (OOP) principles. It leverages Lombok for boilerplate code reduction, Maven for dependency management, and ModelMapper for entity-to-DTO conversion.
Features
CRUD Operations: Create, Read, Update, and Delete operations for National Geographic articles.
Entity-DTO Mapping: Utilizes ModelMapper for seamless conversion between entities and DTOs.
OOP Principles: Implements core OOP concepts for maintainable and scalable code.
Lombok Integration: Reduces boilerplate code for model classes.
Maven Build: Manages dependencies and builds the project efficiently.
Project Structure
controller: REST controllers to handle HTTP requests.
service: Business logic and service layer.
repository: Data access layer to interact with the database.
model: Entity classes representing database tables.
dto: Data Transfer Objects for transferring data between layers.
config: Configuration files for setting up the application context.

Key Dependencies
Spring Boot Starter Web: For building web, including RESTful, applications using Spring MVC.
Spring Boot Starter Data JPA: For accessing data with JPA.
MySQL Connector Java: JDBC driver for MySQL.
Lombok: For reducing boilerplate code in model classes.
ModelMapper: For object mapping between DTOs and entities.
