# Project Name

Employees Management Project

## Overview

Employees Management Project is a REST API project based on Spring Boot that manages employee information. It provides CRUD operations for employee data, including create, read, update, and delete functionalities.

## Tech Stack

- Spring Boot: Used to build fast and configurable Java web applications.
- Hibernate: Used for object-relational mapping and database operations.
- Thymeleaf: Used for server-side rendering of HTML templates.
- AWS EC2: Used for deploying the project on a virtual machine instance.
- AWS RDS: Used for deploying and managing the MySQL database.

## Deployment Information

The project is deployed on an AWS EC2 virtual machine instance and is connected to an AWS RDS MySQL database. You can access the project using the following URL:

- API Endpoint: [http://3.145.12.122:8080/employees/list](http://3.145.12.122:8080/employees/list)

## Getting Started

To run the project locally, follow these steps:

1. Clone the project to your local machine.
2. Configure the database connection information (database URL, username, password).
3. Build the project using Maven: `mvn clean package`.
4. Run the project: `java -jar target/employees-management-projectt.jar`.
5. Access [http://localhost:8080/employees/list](http://localhost:8080/employees/list) in your browser.

## API Documentation

The project provides the following API endpoints:

- GET `/employees/list`: Get all employee information.
- POST `/employees/showFormForAdd`: Create a new employee.
- POST `/employees/save`: Save a new employee.
- PUT `/employees/showFormForUpdate/{id}`: Update specific employee information.
- DELETE `/employees/delete/{id}`: Delete a specific employee.

For detailed API documentation, refer to [API Docs](link-to-api-docs).

## Contributing and License

If you encounter any issues or wish to contribute to the project, please submit an issue or pull request. The project is licensed under the [MIT License](link-to-license).

## Links and Resources

- [Spring Boot Documentation](https://spring.io/projects/spring-boot)
- [Hibernate Documentation](https://hibernate.org/)
- [Thymeleaf Documentation](https://www.thymeleaf.org/)
- [AWS EC2 Documentation](https://aws.amazon.com/ec2/)
- [AWS RDS Documentation](https://aws.amazon.com/rds/)

Please note that the above README file is just an example, and you can modify and customize it according to your project and requirements.


