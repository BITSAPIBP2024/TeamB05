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

## 3. Team B03

#### 1. Overview
The Learning Platform API simplifies the management of users, courses, and progress on a learning platform. It includes functionality for user registration, course enrollment, and progress tracking, catering to the needs of students and administrators.

#### 2. Tech Stack

- **Backend Framework:** Spring Boot  
- **Database:** Not specified  
- **Security:** JWT (JSON Web Token) for authentication  
- **Build Tool:** Maven  
- **Programming Language:** Java  

### Libraries Used:
- Spring Boot Starter Data JPA  
- Spring Boot Starter Web  
- Spring Boot Starter Security  
- Hibernate  
- Jakarta Persistence API  
- Lombok  

#### 3. Key Features

### Authentication & User Management:
- JWT-based authentication for secure access.
- Role-based permissions (Student, Admin).
- User registration, login, and management.

### Course Management:
- Add, update, view, and delete courses.
- Students can browse and filter courses by level.

### Enrollment & Progress Tracking:
- Students can enroll in and deregister from courses.
- Track progress in enrolled courses with options to view, update, or reset progress.

### Admin Features:
- Manage user accounts and courses.
- View enrolled users and their progress.

#### 4. Use Cases

### User Management:
- **Students:** Register, log in, and manage their profiles.
- **Admins:** Update, delete, and search for users, and view their enrolled courses.

### Course Management:
- **Admins:** Create, update, or delete courses and view enrolled users.
- **Students:** Browse, filter, and enroll in courses.

### Progress Tracking:
- **Students:** Track and update progress in enrolled courses.
- **Admins:** Retrieve progress reports for users and courses.

## API Overview

### User Management:
- Endpoints for registration, login, profile management, and user data retrieval.

### Course Management:
- Endpoints for creating, updating, deleting, and retrieving courses.

### Progress Tracking:
- Endpoints for managing progress for individual students or across courses.

---

### Example Usage:
```json
{
  "username": "johndoe",
  "password": "securepassword",
  "role": "Student"
}
```

---

## 4. Team B04


#### 1. Overview
The **Blog API** is a RESTful backend service designed to support blogging platforms. It allows for the management of users, blog posts, and comments with features such as user authentication, role-based access, and secure operations. The API is built with **Node.js** and **Express**, using **MongoDB** for data storage.

---

#### 2. Tech Stack
- **Backend Framework**: Node.js with Express
- **Database**: MongoDB (via Mongoose)
- **Authentication**: JWT (JSON Web Tokens)
- **Password Hashing**: Bcrypt for secure password storage

---

#### 3. Key Features
### User Management
- Secure registration and login.
- JWT-based authentication.
- Role-based access control (User/Admin).
- User profile management.
- Admin privileges to update or delete user accounts.

### Blog Post Management
- Create, read, update, and delete blog posts.
- Search posts by title.
- Admin capabilities to moderate posts.

### Comment Management
- Add, view, update, and delete comments on blog posts.
- Role-based restrictions for comment moderation.

### Security
- Password hashing for secure user credentials.
- Role-based authorization for sensitive operations.

---

#### 4. Use Cases
### User Authentication and Management
- Users can sign up, log in, and manage their profiles.
- Admins can manage user details and roles.

### Content Creation and Management
- Users can create and edit blog posts.
- Admins can moderate all content.

### Engagement Through Comments
- Users can interact with posts by adding comments.
- Admins can review and delete inappropriate comments.

---

