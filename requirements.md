# 📄 Backend Requirements – ALX Airbnb Clone Project

This document describes the functional and technical requirements for three core backend features: **User Authentication**, **Property Management**, and **Booking System**.

---

## 1. 🔐 User Authentication

### 🧩 Functional Requirements
- Users can register as guests or hosts.
- Secure login using email and password.
- JWT-based session authentication.
- Profile updates (name, password, photo, etc.).

### 🧪 API Endpoints

#### ✅ POST `/api/auth/register`
Registers a new user.

**Request:**
```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "password": "SecurePass123!",
  "role": "guest"
}
