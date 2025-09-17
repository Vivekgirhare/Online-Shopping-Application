🛒 Online Shopping Backend System

A backend system for an Online Shopping Application built with Java, Spring Boot, Spring Data JPA, and MySQL.
This project provides RESTful APIs for user and admin authentication, product management, cart management, order handling, and more.
API testing and documentation is enabled with Postman and Swagger.

🚀 Tech Stack & Tools
Java 17+

Spring Framework

Spring Boot

Spring Data JPA

MySQL

Postman

Swagger



📦 Modules
The project consists of the following modules:

Admin Module

Customer Module

Cart & Cart-Product Module

Category Module

Product Module

Orders Module

Address Module

🔑 Features
👨‍💼 Admin Features
Admin Login / Logout

Add / Update / Delete Admin

View Admin details by ID

View all Admins

Update Admin password

👤 Customer Features
Customer Login / Logout

Add / Update / Delete Customer

View Customer details by ID

View all Customers

Update Customer password

🛒 Cart & Cart-Product Features
Add / Remove Product from Cart

Update Product Quantity in Cart

Remove all Products from Cart

View all Products in Cart

View Total Cart Price by Customer ID

🏷️ Category Features
Add / Remove Category

Get all Categories

Get Category by ID

📦 Product Features
View all Products

Add / Update / Delete Product

View Product by ID

View Products by Category

Assign Product to Category

📑 Orders Features
Add Order (with existing / new Address)

Update Order Status

Remove Order

View Order by ID

View Orders by Date / City / Customer

Sort Orders (Ascending / Descending by property)

Pagination Support

🏠 Address Features
Add / Update / Remove Address

View all Addresses

View Address by ID, Pincode, or Building Name

Filter Addresses by Orders / Customers, Pincode, Country & State

Sort Addresses (Ascending / Descending by property)

Pagination Support

⚙️ Installation & Run
Clone the repository

git clone https://github.com/your-username/online-shopping-backend.git
cd online-shopping-backend
Configure your database in application.properties:

server.port=8877
spring.datasource.url=jdbc:mysql://localhost:3306/db22
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=root
spring.datasource.password=root
Run the project:

mvn spring-boot:run
🌐 API Documentation
Base URL:

http://localhost:8877/
Swagger UI:

http://localhost:8877/swagger-ui/index.html
📬 API Testing
You can use Postman or Swagger to test all endpoints.
