# JWT Authentication API (ASP.NET Core 8)

A fully functional **JWT Authentication API** built using **ASP.NET Core 8**, **Entity Framework Core**, and **SQL Server**.  
This project demonstrates secure user authentication, login, password hashing, role-based authorization, and protected endpoints.

---

## 🚀 Features

### 🔐 **Authentication**
- User Registration
- Password hashing using SHA256
- User Login with credential verification
- JWT Token generation
- Token validation & middleware pipeline

### 🛡️ **Authorization**
- Secure endpoints using `[Authorize]`
- Role-based access using:
  ```csharp
  [Authorize(Roles = "Admin")]
