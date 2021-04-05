# Zuul Proxy Gateway
## Microservices Gateway
Zuul proxy acts an entry point to my microservices web application where all the requests are filtered and send to one of the following microservices

## Case
Microservices E-commerce project consists of several microservices. Together they build an e-commerce distributed software system which includes:

### Backend
😃 User service

📦 Order service

🏬 Prodcut service

🌐 Discovery server

🔀 Gateway 

### Frontend
🖥️ Customer application

🖥️ Admin application
## API Endpoints
#### Account service:
```
GET  /account-service/api/users/getAll
GET  /account-service/api/user/getByEmail/{email}
POST  /account-service/api/login
POST  /account-service/api/admin
POST  /account-service/api/register
PUT  /account-service/api/users/{id}
 ````
 ---
#### Order service
```
GET  /order-service/api/orders/getAll
GET  /order-service/api/orders/getAllNew
GET  /order-service/api/orders/getByOrderNumber/{orderNumber}
POST  /order-service/api/orders/
PUT  /order-service/api/orders/{orderNumber}
 ````
  ---
#### Product service
```
GET  /product-service/api/products/getAll
GET  /product-service/api/products/{id}
POST  /product-service/api/products/
PUT  /product-service/api/products/{id}
DELETE /product-service/api/products/{id}
 ````
