# Library Management System

## Problem Statement  
Build a system to manage library operations including book lending, returns, and inventory management.

## Objectives  
- Facilitate efficient management of library books and transactions.  
- Track book availability and lending history.  
- Allow librarians to manage books and users.  
- Provide search and report functionalities.

## Features  
- Add and remove books and users.  
- Book lending and return functionality with status updates.  
- Search books by title, author, or category.  
- Reports on overdue books and user borrowing history.  
- Secure access for librarians using Spring Security.

## Entities  
- **Book:** `bookId`, `title`, `author`, `category`, `availability`  
- **User:** `userId`, `name`, `membershipType`  
- **Transaction:** `transactionId`, `bookId`, `userId`, `issueDate`, `returnDate`, `status`

## Technologies Used  
- Java  
- Spring Boot  
- Spring Data JPA  
- H2 Database  
- Spring Security  

## How to Run  
1. Clone the repository.  
2. Open in your preferred IDE.  
3. Run the Spring Boot application (`LibraryManagementSystemApplication.java`).  
4. Access H2 Console at `http://localhost:8080/h2-console` (JDBC URL: `jdbc:h2:mem:testdb`) if needed.

## Author  
Divya Adabala

---

Feel free to customize this further if you want to add screenshots, API documentation, or usage examples.
