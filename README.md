# shopify-ecommerce
“E-commerce website built with Shopify features including product list, add to cart, order, and payment integration.

This is the backend service for the Shopify-style e-commerce website, developed using **Spring Boot**. It handles products, users, carts, orders, and payment APIs.

## 📌 Features
- User Registration and Login (JWT-based)
- Product Management (CRUD)
- Cart API (add, remove, update items)
- Order API (place and track orders)
- Role-based access control (Admin, Customer)
- Dummy Payment Integration
- RESTful API with JSON

## ⚙️ Tech Stack
- **Framework**: Spring Boot
- **Database**: MySQL / PostgreSQL / H2
- **ORM**: Hibernate + Spring Data JPA
- **Security**: Spring Security with JWT
- **Documentation**: Swagger UI
- **Build Tool**: Maven

## 🔐 API Authentication
- JWT Token is required for protected routes (e.g., /cart, /order)
- Admin endpoints protected with role checks



