
# PG-Management

This project is a PG (Paying Guest) Management System developed using Spring Boot and Angular, with MySQL as the database.

## Table of Contents
#### Introduction
#### Features
#### Technologies Used
#### Installation
#### Usage
#### Contributing
#### License

## Introduction
The PG Management System is designed to manage the operations of a PG accommodation business. It provides functionalities for managing rooms, tenants, bookings, payments, and more.
## Features
#### User authentication and authorization
#### Room management
#### Tenant management
#### Booking management
#### payment management
#### Dashboard for administrators

## Technologies Used
#### Backend: Java, Spring Boot 
#### Frontend: TypeScript, Angular
#### Database: MySQL

# Installation
### Prerequisites
#### Java 8 or higher
#### Node.js
#### MySQL
## Backend Setup
1. Clone the repository:

```
git clone https://github.com/yourusername/pg-management-system.git
cd pg-management-system/backend
```
2.Update the application.properties file with your MySQL database credentials:
```
spring.datasource.url=jdbc:mysql://localhost:3306/yourdbname
spring.datasource.username=yourusername
spring.datasource.password=yourpassword
```
3.Build and run the Spring Boot application:
```
mvn clean install
mvn spring-boot:run
```
## Frontend Setup
1. Navigate to the frontend directory:
```
cd ../frontend
```
2. Install the dependencies:
```
npm install
```
3. Run the Angular application:
```
ng serve
```
 ## Database Setup

1.Create a MySQL database:
```
CREATE DATABASE PG-ManagementDATAStore;
```
2.The application will automatically create the required tables upon running.

## Usage
1. Access the frontend application at http://localhost:4200.
2. Log in with your credentials.
3. Use the dashboard to manage rooms, tenants, bookings, and payments.
## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.
## License
This project is licensed under the MIT License. See the LICENSE file for details.






