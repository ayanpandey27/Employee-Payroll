# Employee Payroll System

## Overview
The **Employee Payroll System** is a Java and Spring Boot-based application designed to manage employee salary details efficiently. It provides CRUD operations for employee records and payroll processing, ensuring seamless salary management and compliance tracking.

## Features
- **Employee Management**: Add, update, delete, and view employee details.
- **Payroll Processing**: Calculate salaries based on predefined rules.
- **Leave & Attendance Tracking**: Maintain records for accurate payroll processing.
- **Tax & Deductions Calculation**: Automate tax and other deductions.
- **Role-Based Access Control**: Secure data with user roles (Admin, Employee, HR).
- **Database Integration**: Store and manage payroll data using MySQL/PostgreSQL.
- **RESTful API**: Expose endpoints for external applications.
- **Swagger API Documentation**: Interactive documentation for testing.

## Technologies Used
- **Java 17+**
- **Spring Boot 3+**
- **Spring Security & JWT**
- **Spring Data JPA (Hibernate)**
- **MySQL/PostgreSQL**
- **Swagger (OpenAPI)**
- **Lombok**
- **Docker (Optional)**

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ayanpandey27/Employee-Payroll.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Employee-Payroll
   ```
3. Configure the database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/payroll_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   spring.jpa.hibernate.ddl-auto=update
   ```
4. Build and run the application:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```
5. Access the API documentation at:
   ```
   http://localhost:8080/swagger-ui/
   ```

## Usage
- **Register/Login**: Secure authentication via JWT.
- **Manage Employees**: Add, update, or delete employee records.
- **Payroll Calculation**: Process salaries, tax deductions, and benefits.
- **Admin Controls**: Assign roles and permissions.

## Future Enhancements
- **Integration with Payment Gateways**: Automate salary disbursement.
- **Cloud Deployment**: Deploy on AWS/GCP.
- **Microservices Architecture**: Modularize employee and payroll services.
- **Multi-Tenancy Support**: Manage payroll for multiple companies.

## License
This project is open-source and available under the MIT License.
