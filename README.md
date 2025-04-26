# BankingApplication
Simple Banking Management REST API built with Spring Boot, Hibernate (JPA), and MySQL.
This is a RESTful Banking Application built using Spring Boot, Spring Data JPA (Hibernate), and MySQL.
It allows users to manage bank accounts with core functionalities like:

✅ Create an account

💰 Deposit money

💸 Withdraw money

🔍 View account details

📋 List all accounts

❌ Delete account

🛠️ Tech Stack
Java

Spring Boot

Spring Data JPA (Hibernate)

MySQL

Maven

REST API

📬 API Endpoints (Sample)

Method	Endpoint	Description
POST	/api/accounts	Create a new account
GET	/api/accounts/{id}	Get account by ID
PUT	/api/accounts/{id}/deposit	Deposit into account
PUT	/api/accounts/{id}/withdraw	Withdraw from account
GET	/api/accounts	Get all accounts
DELETE	/api/accounts/{id}	Delete account by ID
🧪 How to Run Locally
Clone the repository

Set up MySQL and update the credentials in application.properties

Run using your IDE or mvn spring-boot:run

Use Postman or any API tool to test endpoints
