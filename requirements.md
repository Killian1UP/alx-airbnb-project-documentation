# alx-airbnb-project-documentation

# 📄 Backend Feature Requirements – Airbnb Clone

This document outlines the technical and functional requirements for three core backend features of the Airbnb Clone project:

1. User Management  
2. Property Listings Management  
3. Booking Management

These requirements are structured to guide development, testing, and integration with frontend or mobile clients.

---

## 1️⃣ User Management

### 🔐 Feature Overview

Enables guests and hosts to register, authenticate, and manage their profiles securely.

---

### 🧩 Endpoints

#### 1.1 Register User  
**POST** `/api/users/register/`

##### 🔸 Request
```json
{
  "role": "guest",
  "name": "Jane Doe",
  "email": "jane@example.com",
  "password": "securePass123"
}
