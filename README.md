---

# 🚀 User Management API with Auth (JWT) + API Key

This API allows user management with secure authentication using JWT tokens and API keys. It provides endpoints for user registration, authentication, and CRUD operations on user data.

## 📌 Installation

### ✅ Prerequisites

- Node.js (>=16.x)
- NestJS (Nest CLI)
- PostgreSQL (or any other configured database)

### 📥 Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rHarylala/RESTful-API.git
   cd RESTful-API
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure the database in `ormconfig.json` or `.env`:**
   ```bash
   DB_HOST=localhost
   DB_PORT=5432
   DB_USERNAME=your_username
   DB_PASSWORD=your_password
   DB_NAME=userapi
   ```

4. **Run the application:**
   ```bash
   npm run start
   ```

5. **Database migrations (optional):**
   If you're using TypeORM, run the migrations to create necessary tables:
   ```bash
   npm run migration:run
   ```

## 📡 Routes API

### Authentication & User Management

- **POST /api/login**  
  User login (Returns a JWT token, API Key)

- **POST /api/register**  
  Register a new user

- **GET /api/users**  
  List all users (Requires authentication)

- **PUT /api/users/:id**  
  Update a user's data (Requires authentication)

- **DELETE /api/users/:id**  
  Delete a user (Requires authentication)

### Auth

- **POST /api/auth/refresh-token**  
  Refresh JWT token when expired

## 📖 API Documentation

- **Swagger UI:**  
  [http://localhost:3000/swagger](http://localhost:3000/swagger)
  
- **Postman Collection:**  
  You can download the Postman collection [here](link_to_postman_collection).

---

© Hary Lala RABENAMANA - 2025

---
