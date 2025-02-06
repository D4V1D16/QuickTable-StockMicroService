# Inventory Service

The **Inventory Service** is a microservice responsible for managing the inventory of products in a restaurant. It ensures that stock levels are updated in real-time and provides essential functionality for adding, updating, and retrieving product information. This service is built using **Go** with the **Gin Framework** for high performance and scalability.

---

## Key Features

- **Product Management**:
  - Add new products to the inventory.
  - Update stock levels for existing products.
  - Retrieve a list of all available products.

- **Real-Time Stock Updates**:
  - Handles stock updates via RESTful API endpoints.

- **Efficient Data Access**:
  - Uses **MySQL** for persistent storage and **Redis** for caching frequently accessed inventory data.

---

## Tech Stack

- **Language**: Go (Golang)
- **Framework**: [Gin Framework](https://gin-gonic.com/) (Fast HTTP web framework)
- **Database**:
  - **MySQL**: For persistent storage of inventory data.
  - **Redis**: For caching to improve read performance.

---

## Endpoints

### REST API

- `GET /inventory`: Retrieve a list of all products in the inventory.
- `POST /inventory`: Add a new product to the inventory.
- `PUT /inventory/:id`: Update the stock level of a specific product.

---

## Tools & Libraries

- **Gin Framework**: Lightweight and fast HTTP router for Go.
- **GORM**: ORM library for interacting with MySQL.
- **go-redis**: Redis client for Go to manage caching.

![image](https://github.com/user-attachments/assets/2c99e140-2a29-49ca-9174-f68e23ce1752)
