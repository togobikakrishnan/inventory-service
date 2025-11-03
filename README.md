# Inventory Management System

A Spring Boot RESTful API for managing **products** and **orders** with transactional integrity, validation, and in-memory H2 database.

---

## Project Overview

This project demonstrates a inventory management system where:
- **Products** can be created, updated and listed.
- **Orders** can be placed with multiple items.
- Stock quantities are updated automatically when an order is placed.
- Transactions ensure **data consistency** — if any part of an order fails, all changes roll back.
- Includes **DTOs**, **Service Layer**, **Exception Handling**, and **Unit Tests**.

---

## Setup Instructions
### Prerequisites
- Java 17+
- Maven
- IDE (IntelliJ / Eclipse)

### Build and Run

1. **Clone the repository**

   git clone https://github.com/your-username/inventory-service.git
   
   import inventory-service
      
2. ** Build the project**

   mvn clean install
     
3. ** Run the application**

   Run the main class:

   src/main/java/cams/inv/service/ApplicationInitializer.java
	
4. **Access the application**

   http://localhost:8080
	
5. **H2 Database Console**

   http://localhost:8080/h2-console
	
   JDBC URL: jdbc:h2:file:./data/inventory
	
   Username: sa
	
   Password: (leave blank)


