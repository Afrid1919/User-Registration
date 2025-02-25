This is a User Registration System built using Spring Boot, Java, MySQL, HTML, and CSS. The system allows users to register, login, and manage their accounts securely. It follows MVC architecture and uses Spring Security for authentication and authorization.

## Technologies Used

Backend: Java, Spring Boot, Spring MVC, Spring Security

Database: MySQL

Frontend: HTML, CSS, Bootstrap

Build Tool: Maven

ORM: Hibernate JPA

## Features

- User Registration with form validation
- Secure Password Encryption using BCrypt
- User Login and Authentication
- Role-Based Access Control (Admin/User)
- Session Management
- Profile Management

## Setup and Installation

1. Clone the Repository

git clone https://github.com/your-username/user-registration.git
cd user-registration

2. Configure the Database

Update the application.properties file with your MySQL credentials:

spring.datasource.url=jdbc:mysql://localhost:3306/user_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect

3. Build and Run the Project

Using Maven:

mvn clean install
mvn spring-boot:run

Or, Run the JAR file:

java -jar target/user-registration-0.0.1-SNAPSHOT.jar

## Usage

Open http://localhost:8080/register in your browser.

Fill out the registration form and submit.

Login using your credentials at http://localhost:8080/login.

Access the dashboard and manage your profile.

## Security Implementations

BCrypt Password Encoding for secure password storage.

Spring Security for authentication & authorization.


## Contributing

Fork the repository.

Create a new branch (git checkout -b feature-branch).

Commit your changes (git commit -m 'Added new feature').

Push to the branch (git push origin feature-branch).

Create a Pull Request.
