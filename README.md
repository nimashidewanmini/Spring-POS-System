 
![Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/Spring_Framework_Logo_2018.svg/368px-Spring_Framework_Logo_2018.svg.png?20181210015349)


# Spring POS System

## Introduction
This project is designed to maintain a proper layered architecture for a web application using Spring Boot, MySQL, and AJAX. The goal is to ensure a clean separation of concerns, enhancing maintainability, scalability, and testability.



## Tech Stack 

- **Backend Framework:** Spring

- **Database:** MySQL

- **Client-side Communication:** AJAX

- **Database Configuration:** Spring Data JPA (with Hibernate)

- **Logging:** slf4j,logback

## Architecture Overview

The application follows a layered architecture comprising the following layers:

**1.** **Presentation Layer:** Manages the user interface and client-side interactions. In Spring, this can be implemented using @Controller classes, @RestController for REST APIs, and Thymeleaf or other templating engines for server-side rendering.

**2.** **Business Logic Layer:** Contains the core functionality and business rules. This can be organized in Spring as @Service classes where all business logic is handled.

**3.** **Data Access Layer:** Handles direct interactions with the database. Spring Data JPA simplifies this by providing @Repository classes that automatically manage CRUD operations.


## Setup and Configuration


### Prerequisites

- **JDK 21**
- **Spring compatible application server (e.g., Tomcat,WildFly, GlassFish)**
- **MySQL server**
- **Maven**

### Clone the repository:

```bash
https://github.com/nimashidewanmini/Spring-POS-System.git
```  

## Database Configuration

**1.Create a MySQL database.**

**2.Configure JNDI for database connectivity:**
- Define a JNDI resource in your application server's configuration.

- Example configuration for Tomcat:


Logging

- **DEBUG:** Fine-grained information for debugging.
- **INFO:** General information about application progress.
- **WARN:** Potentially harmful situations.
- **ERROR:** Error events that might still allow the application to continue running.

 ## API Documentation

To view this project API Documentation

```bash
 https://documenter.getpostman.com/view/35385603/2sAXxV6ViM
```
Refer to the [Postman API Documentation](https://documenter.getpostman.com/view/35385603/2sAXxV6ViM) for detailed API endpoints and usage instructions.

## License
This project is licensed under the MIT License - see the [MIT License](LICENSE) file for details. 

<br>

<p align="center">
  &copy; 2024 Nimashi Dewanmini
</p>
