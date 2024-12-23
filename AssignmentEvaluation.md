# Project Evaluation 

## 1. Team A01
#### 1. Overview
The primary goals of the APIs in this project are to provide a robust and secure mechanism for managing gold provenance and verification using blockchain technology. The APIs are used to support the entire lifecycle of gold transactions, from registration to verification and transfer The APIs are designed to facilitate interactions between different roles in the system, namely "Buyers" and "Sellers." These roles are differentiated through JWT tokens, allowing for secure and role-based access to various functionalities. The APIs ensure the authenticity and traceability of gold by allowing Sellers to register gold on the blockchain, and enabling Buyers to verify and transfer gold securely.

#### 2. Tech Stack

- **JavaScript (72.4%)**: Primarily used for developing the API logic, possibly using Node.js for server-side scripting and Express.js for routing.
- **CSS (22.6%)**: For styling any web interfaces that interact with the APIs.
- **Solidity (3.4%)**: Used for writing smart contracts, which could be integrated with the APIs for blockchain interaction.
- **HTML (1.6%)**: To structure the web content that interacts with the APIs.

#### 3. Key Features

- **RESTful API Endpoints**: For various CRUD operations, enabling interactions with the backend database.
- **Smart Contract Integration**: APIs that interact with Ethereum blockchain through Solidity smart contracts.
- **User Authentication**: Secure user authentication and authorization mechanisms.
- **Responsive Web Interface**: Web interfaces styled with CSS to ensure responsiveness and usability across different devices.

#### 4. Use Cases

- **Decentralized Finance (DeFi)**: APIs for financial transactions involving smart contracts for secure and transparent operations.
- **Web Applications**: APIs that serve as the backend for web applications, providing functionalities such as data retrieval, user management, and content delivery.
- **Educational Tools**: Demonstrating API development and blockchain integration for educational purposes in an academic setting.

#### 5. Areas of Improvement

- **Documentation**: Comprehensive and clear documentation can greatly aid new contributors and users in understanding the project’s functionality and setup processes.
- **Testing**: Implementing robust testing frameworks and ensuring high test coverage can improve the reliability and stability of the APIs.
- **User Experience (UX)**: Regular updates and feedback collection from users can help in refining the interface and ensuring a seamless user experience.
- **Security Audits**: Given the use of Solidity and potential blockchain elements, regular security audits can help in identifying and mitigating vulnerabilities in smart contracts.


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
