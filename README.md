# 🧪 Herokuapp — REST API Testing Suite

Automated API test collection for a multi-role web application,
covering the full user lifecycle and task management workflows.

## 📋 What's Tested

### 👤 User Management
- Registration for 3 roles: Admin, Teacher, Student
- Login with JWT Bearer token extraction
- Get user info by username
- Activate users with role assignment (ROLE_ADMIN, ROLE_USER_STUDENT, ROLE_USER_TEACHER)
- Delete users

### ✅ Tasks
- Create, read, update (PUT & PATCH), delete tasks
- Assign tasks to users
- Update task solve status

### 🔴 Sad Path
- Invalid login attempts
- Bad registration requests

## 🛠️ Tech Stack
- Postman
- REST API
- JWT Authentication
- JSON / Environment Variables

## ✨ Key Features
- Chained requests using dynamic variables (`{{token}}`, `{{id_student}}`, etc.)
- Assertions on status codes, response time, headers, and field values
- Happy path + negative test cases
- Environment-based configuration
