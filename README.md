
# Employee Management System

## Overview

This project is an Employee Management System developed using Spring Boot. It provides basic functionality for managing employee records, including insertion, viewing, and deletion operations.

## Features

- Insert new employee records
- View existing employee records
- Delete employee records

## Technologies Used

- Spring Boot
- Spring Data JPA
- Thymeleaf (for web-based views)
- MySQL (or your preferred database)

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or later
- Maven
- MySQL (or another relational database of your choice)

### Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/employee-management-system.git
    cd employee-management-system
    ```

2. Configure the database:

    - Open `src/main/resources/application.properties`.
    - Update the database URL, username, and password according to your database configuration.

3. Build and run the application:

    ```bash
    mvn spring-boot:run
    ```

4. Open your browser and navigate to `http://localhost:8080` to access the application.

## Usage

- Insert Employee: Navigate to the "Insert" page and fill in the required information.
- View Employees: Navigate to the "View" page to see the list of existing employees.
- Delete Employee: Navigate to the "View" page, find the employee you want to delete, and click the delete button.



## Acknowledgments

- [Spring Boot](https://spring.io/projects/spring-boot)
- [Thymeleaf](https://www.thymeleaf.org/)


