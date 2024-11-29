# Welcome to Trade-Tix Docs

Trade-Tix: Don't waste your tickets.


&nbsp;





## How to run

To run the project locally, follow these steps:

&nbsp;


### Frontend

1. **Clone the repo**:
    ```
    git clone https://github.com/pravin-pk/TradeTix-frontend.git
    ```
2. **Start the Development Server**:
    ```
    npm run start
    ```

 &nbsp;


### Backend

1. **Clone the repo**:
    ```
    git clone https://github.com/pravin-pk/TradeTix-backend.git
    ```
2. **Move to k8s**:
    ```
    cd tradetix-backend/k8s
    ```
3. **Run the Docker command**:
    ```
    docker-compose up -d
    ```
4. **Move back to the main folder**:
    ```
    cd ..
    ```
5. **Run the app**:
    ```
    npm run dev
    ```

&nbsp;





## Project Structure

| File or Folder | Purpose                                |
|----------------|----------------------------------------|
| `controllers/` | Controller for the resource           |
| `middlewares/` | Auth Middleware                       |
| `models/`      | Domain Model                          |
| `providers/`   | External services                     |
| `routers/`     | Routing for resource                  |




&nbsp;
## Technology Stack
We agreed to use the following technology stack:

- **Node.j, Express, TypeScript**: Programming languag for backend.
- **Angular**: For the Frontend.
- **MongoDB**: For the Database.
- **GitHub**: For source code management.
- **MetaMask, SmartContract**: For crypto transaction.


&nbsp;

## Requirement : Why Is There a Need for a Ticket Reselling Application?
&nbsp;

## 1. Overview
The ticket reselling application provides a platform for individuals to buy and sell event tickets securely, transparently, and efficiently. This document outlines the primary reasons and business needs driving the development of this application.

---

## 2. Purpose
To address the gaps and challenges faced by consumers and resellers in the current ticketing market. The application aims to provide a seamless, user-friendly platform to facilitate ticket reselling, ensuring security, fair pricing, and convenience.

---

## 3. Target Audience
- **Primary Users**: Individuals looking to resell or purchase event tickets.
- **Secondary Users**: Event organizers, ticketing agencies, and marketers.

---

## 4. Problem Statement

### 4.1 For Buyers
- **Scalping**: Buyers often face inflated ticket prices due to resellers exploiting demand.
- **Fake Tickets**: Many buyers fall victim to fraudulent or duplicate tickets.
- **Limited Options**: Current platforms offer restricted access to tickets for high-demand events.

### 4.2 For Sellers
- **Inconvenience**: No dedicated, easy-to-use platform for securely reselling tickets.
- **Price Inefficiency**: Sellers often cannot set fair prices due to unregulated platforms or lack of demand insights.

---

## 5. Business Needs

### 5.1 Consumer Demand
- Events with limited seating often sell out quickly, creating a need for reselling.
- Buyers frequently seek last-minute tickets, creating a secondary market.

### 5.2 Security and Trust
- Building a trusted environment to minimize fraud risks.

### 5.3 Convenience
- Simplified process for listing tickets and matching buyers and sellers.
- web application for easy access.


### 5.4 Analytics and Insights
- Providing buyers with transparency in pricing and availability.

---

## 6. Goals and Objectives

### 6.1 Goals
- To create a marketplace for secure and transparent ticket reselling.
- To ensure an exceptional user experience for both buyers and sellers.

### 6.2 Objectives
- Facilitate seamless payment processing with buyer/seller protection.

---

## 7. Functional Requirements
- **User Registration**: Secure sign-up and profile management.
- **Listing Tickets**: Options to upload ticket.
- **Secure Payment Gateway**: Enable transactions with multiple payment options.

---

## 8. Non-Functional Requirements
- Data security to protect user information and payment details.
- Minimal downtime for a seamless experience.

---

## 9. Conclusion
A ticket reselling application addresses the growing need for a reliable, secure, and transparent platform for ticket exchanges. By solving key pain points for buyers and sellers, the application has the potential to revolutionize the secondary ticketing market, ensuring customer satisfaction and driving significant business value.








