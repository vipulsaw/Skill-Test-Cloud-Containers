# Skill-Test-Cloud-Containers
# Microservices-Task

## Overview
This document provides details on testing various services after running the `docker-compose` file. These services include User, Product, Order, and Gateway Services. Each service has its own endpoints for testing purposes.

---

## Services and Endpoints

### **User Service**
- **Base URL:** `http://107.21.154.191:3000`
- **Endpoints:**
  - **List Users:**  
    ```
    curl http://107.21.154.191:3000/users
    ```
    Or open in your browser: [http://107.21.154.191:3000/users](http://107.21.154.191:3000/users)

---

### **Product Service**
- **Base URL:** `http://107.21.154.191:3001`
- **Endpoints:**
  - **List Products:**  
    ```
    curl http://107.21.154.191:3001/products
    ```
    Or open in your browser: [http://107.21.154.191:3001/products](http://107.21.154.191:3001/products)

---

### **Order Service**
- **Base URL:** `http://107.21.154.191:3002`
- **Endpoints:**
  - **List Orders:**  
    ```
    curl http://107.21.154.191:3002/orders
    ```
    Or open in your browser: [http://107.21.154.191:3002/orders](http://107.21.154.191:3002/orders)

---

### **Gateway Service**
- **Base URL:** `http://107.21.154.191:3003/api`
- **Endpoints:**
  - **Users:**  
    ```
    curl http://107.21.154.191:3003/api/users
    ```
  - **Products:**  
    ```
    curl http://107.21.154.191:3003/api/products
    ```
  - **Orders:**  
    ```
    curl http://107.21.154.191:3003/api/orders
    ```

---

## Instructions
1. Start all services using the `docker-compose` file:
   ```
   docker-compose up
   ```
2. Once the services are running, use the above endpoints to verify the functionality.

Happy testing!
