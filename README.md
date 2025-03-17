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

3. **Configure the database in `.env`:**
   ```bash
   DATABASE_URL="postgres://username:password@localhost:5432/user_api"
   ```

4. **Run the application:**
   ```bash
   npm run start
   ```

5. **Generate Prisma client**      
   ```bash
   npx prisma generate
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


## 📖 API Documentation

- **Swagger UI:**  
  [http://localhost:3000/swagger](http://localhost:3000/swagger)
  
- **Postman Collection:**  
  You can download the Postman collection [here](https://github.com/rHaryLala/RESTful-API/blob/master/REST%20API%20on%20NestJs%20-%20CRUD%2C%20test%20%26%20variable.postman_collection.json).

---

© Hary Lala RABENAMANA - 2025

---
