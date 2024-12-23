# FastAPI Inventory Microservices

## Overview
This project implements an **Inventory Management System** using **FastAPI**, designed with a microservices architecture. The system provides endpoints for managing products, stock levels, and related inventory operations, ensuring scalability and flexibility.

## Features
- **Product Management**: Add, update, view, and delete products.
- **Stock Management**: Track stock levels, update quantities, and manage inventory transactions.
- **Microservices Architecture**: Modular services for product, stock, and other related functionalities.
- **Asynchronous API**: High-performance, non-blocking endpoints with FastAPI.
- **Extensible Design**: Easy to integrate with additional services, such as analytics or order management.

## Technologies Used
- **FastAPI**: Python-based framework for building APIs.
- **SQLAlchemy**: Database ORM for managing data models and queries.


## Core Endpoints
### Product Service
- **GET /products**: Retrieve a list of all products.
- **POST /products**: Add a new product.
- **PUT /products/{id}**: Update an existing product.
- **DELETE /products/{id}**: Remove a product.

### Stock Service
- **GET /stocks**: Retrieve current stock levels.
- **POST /stocks**: Add stock to inventory.
- **PUT /stocks/{id}**: Update stock details.
- **DELETE /stocks/{id}**: Remove stock from inventory.

## Running the Application
1. Start individual services (e.g., product_service, stock_service) locally or via Docker.
2. Use an API testing tool (e.g., Postman) to interact with the endpoints.

## Purpose
This project demonstrates a modular and scalable approach to building an inventory management system. It is suitable for learning microservices architecture or as a base for developing a production-ready solution.

---

Explore the codebase and extend its functionalities as needed. Happy coding! 🚀

