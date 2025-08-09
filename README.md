# 📝 Productivity App API  
A Node.js backend for managing **users** and **tasks**, with JWT authentication and file uploads.  

## 🚀 Features  
✅ **User Authentication** (Signup, Login, Protected Routes)  
✅ **Task Management** (Create, Read, Update, Delete Tasks)  
✅ **File Uploads** (User profile pictures)  
✅ **JWT Security** (Token-based access control)  

---

## 🔧 Postman API Tests  

| Endpoint               | Method | Description                          | Screenshot |
|------------------------|--------|--------------------------------------|------------|
| `POST /users/signup`   | POST   | Register new user (photo upload)     |            |
| `POST /users/login`    | POST   | Login to get JWT token               |            |
| `GET /users`           | GET    | Fetch all users                      |            |
| `GET /users/profile`   | GET    | Get logged-in user's profile         |            |
| `PATCH /users/profile` | PATCH  | Update user details                  |            |
| `POST /tasks`          | POST   | Create new task                      |            |
| `GET /tasks`           | GET    | Fetch user's tasks                   |            |
| `GET /tasks/:id`       | GET    | Get specific task by ID              |            |
| `PATCH /tasks/:id`     | PATCH  | Update task                          |            |
| `DELETE /tasks/:id`    | DELETE | Delete task                          |            |

---