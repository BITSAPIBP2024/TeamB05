# Project Evaluation 

## 1. Team B01

#### 1. Overview
The Dynamic Blog API is a highly scalable and feature-rich solution designed for managing blog posts within an organization. It supports robust role-based authorization with JWT authentication, allowing admins to manage blog content and users to interact with it seamlessly. The API includes advanced features like pagination, sorting, API versioning, and AI-driven image validation, ensuring a modern and efficient blogging experience.

#### 2. Tech Stack
- **Backend**: Java, Spring Boot
- **Database**: MySQL
- **Caching**: Redis
- **API Documentation**: Swagger
- **Testing**: Bruno

#### 3. Key Features
- **Role-Based Authorization**: Admins can manage blog posts, categories, logos, and titles, while users can read posts, leave comments, and view content. Admins can also promote or demote user roles.
- **Advanced Capabilities**: Pagination & sorting, API versioning, Redis caching, rate limiting, AI-driven image validation, and custom exceptions for better debugging.
- **Documentation**: Detailed Swagger documentation and a pre-configured Bruno collection for API testing.

#### 4. Use Cases
- **Blog Management**: Organizations can use the API to create, read, update, and delete blog posts and categories.
- **User Interaction**: Users can read blog posts, leave comments, and interact with the content.
- **Admin Functions**: Admins can manage user roles and ensure the smooth operation of the blog platform.

#### 5. Areas of Improvement
- **Scalability**: Implementing more advanced caching mechanisms and optimizing database queries can enhance performance for high-traffic scenarios.
- **Security**: Regular security audits and updates to address any vulnerabilities can ensure the API remains secure.
- **Integration**: Expanding the API to support more integrations with third-party services can increase its versatility and usability in diverse environments.

---

## 2. Team B02

#### 1. Overview
The project demonstrates a microservices architecture for an e-commerce application. It includes three main services:
- **Product Service**: Manages product information.
- **Inventory Service**: Handles stock management.
- **Order Service**: Processes customer orders and coordinates with other services.

Each service operates independently and communicates via REST APIs. The project showcases a modular design that allows each service to scale independently and maintain its own database, ensuring decoupling and scalability.

#### 2. Tech Stack
- **Backende**: Java 11
- **Framework**: Spring Boot
- **Database**: PostgreSQL
- **Build Tool**: Maven
- **Additional Tools**: Spring Cloud, Spring Data JPA, Spring Actuator, Spring Cloud Netflix Eureka

#### 3. Key Features
- **Product Service**: CRUD operations for product management.
- **Inventory Service**: Tracks and updates product stock levels.
- **Order Service**: Processes orders and validates stock availability.
- **Scalable Design**: Each microservice is modular and can be scaled independently.
- **Database Separation**: Each service has its own database to ensure decoupling.

#### 4. Use Cases
- **E-commerce Platform**: Facilitates the creation and management of an online store with products, inventory, and order processing.
- **Inventory Management**: Helps businesses manage stock levels and ensure product availability.
- **Order Processing**: Validates and processes customer orders, ensuring a smooth transaction flow.

#### 5. Areas of Improvement
- **Error Handling**: Enhance error handling mechanisms to provide more informative and user-friendly error messages.
- **API Rate Limiting**: Implement rate limiting to prevent abuse and ensure fair usage of the APIs.
- **Testing**: Increase test coverage, particularly integration tests, to ensure robust interactions between microservices.
- **Security**: Strengthen security measures, such as implementing OAuth2 for secure API access and ensuring data encryption both in transit and at rest.
- **Performance Optimization**: Analyze and optimize the performance of APIs to handle larger volumes of requests efficiently.
- **Monitoring and Logging**: Improve monitoring and logging to quickly identify and resolve issues in a production environment.

---

## Team B10
#### 1. Overview
The Service Booking System is a Spring Boot-based platform designed to facilitate service booking between clients and companies. It provides a RESTful API architecture that allows service providers to advertise their services and clients to discover, book, and review these services. The platform includes features for user authentication, service advertisement management, booking management, and review submission.

#### 2. Technology Stack
- **Backend Framework**: Spring Boot
- **Database**: MySQL
- **Security**: JWT (JSON Web Token) for authentication
- **Build Tool**: Maven
- **Programming Language**: Java
- **Libraries**:
  - Spring Boot Starter Data JPA
  - Spring Boot Starter Web
  - Spring Boot Starter Security
  - Lombok
  - JJWT (Java JWT)
  - Hibernate
  - Jakarta Persistence API
  - Vaadin JSON

#### 3. Key Features
- **Authentication & User Management**:
  - JWT-based authentication
  - Role-based access control (Client, Company)
  - Secure registration and login
- **Client Features**:
  - Browse and search service advertisements
  - Book services
  - View booking history
  - Submit reviews for services
- **Company Features**:
  - Create, update, and delete service advertisements
  - View and manage received bookings
  - Update booking statuses
- **Error Handling**:
  - Custom error codes and messages
  - Global exception handling
- **Rate Limiting**:
  - Limits requests to 50 per minute per IP address

#### 4. Use Cases
- **User Registration**:
   - Clients and companies can register on the platform with their email and password.
- **User Authentication**:
   - Users can log in using their credentials and receive a JWT token for authenticated requests.
- **Service Advertisement Management**:
   - Companies can create, update, and delete service advertisements.
- **Service Booking**:
   - Clients can browse and search for services, and book them for specific dates.
- **Booking Management**:
   - Companies can view and manage bookings, updating their statuses as needed.
- **Review Submission**:
   - Clients can submit reviews for services they have booked.

#### Areas of Improvement
- **Error Handling**:
   - Improve error messages to be more user-friendly and informative.
   - Ensure consistent error handling across all endpoints.
- **Validation**:
   - Add more comprehensive validation for user inputs, especially during registration and booking.
- **Security**:
   - Implement stronger password policies and validation.
   - Consider adding two-factor authentication (2FA) for enhanced security.
- **Scalability**:
   - Optimize database queries and indexing for better performance with large datasets.
   - Implement caching mechanisms for frequently accessed data.
- **Testing**:
   - Increase test coverage, especially for edge cases and error scenarios.
   - Implement integration tests to ensure the smooth functioning of the entire system.
- **Documentation**:
   - Improve API documentation to include detailed descriptions of endpoints, request/response formats, and example usage.
   - Provide user guides and developer documentation for easier onboarding and usage.
- **User Experience**:
   - Enhance the user interface for better usability and accessibility.
   - Provide more detailed feedback to users during interactions, such as booking confirmations and error 
