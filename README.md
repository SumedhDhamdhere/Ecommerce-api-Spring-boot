# Ecommerce-api-Spring-boot

🧑‍💻 Technologies Used
----------------------
- Spring Boot
- JWT Authentication
- Spring Security
- RESTful API
- In-Memory H2 Database

🌐 API Endpoints
----------------

🔓 Public APIs
--------------
POST /api/public/login
GET  /api/public/product/search?keyword=...

👤 Consumer APIs (Require JWT with CONSUMER role)
-------------------------------------------------
GET    /api/auth/consumer/cart
POST   /api/auth/consumer/cart
PUT    /api/auth/consumer/cart
DELETE /api/auth/consumer/cart

🧑‍💼 Seller APIs (Require JWT with SELLER role)
-----------------------------------------------
GET    /api/auth/seller/product
GET    /api/auth/seller/product/{productId}
POST   /api/auth/seller/product
PUT    /api/auth/seller/product
DELETE /api/auth/seller/product/{productId}
