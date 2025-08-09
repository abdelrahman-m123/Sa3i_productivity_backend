# Sa3i Productivity App Backend
A Node.js backend for managing **users** and **tasks**, with JWT authentication and file uploads.  

##  Features  
 **User Authentication** (Signup, Login, Protected Routes)  
 **Task Management** (Create, Read, Update, Delete Tasks)  
 **File Uploads** (User profile pictures)  
 **JWT Security** (Token-based access control)  

---

## 🔧 Postman API Tests  

| Endpoint               | Method | Description                          | Screenshot |
|------------------------|--------|--------------------------------------|------------|
| `POST /users/signup`   | POST   | Register new user (photo upload)     |         <img width="1732" height="865" alt="image" src="https://github.com/user-attachments/assets/a746e885-4ee0-43e6-a44d-bba8df7192ef" />  |
| `POST /users/login`    | POST   | Login to get JWT token               |    <img width="1707" height="827" alt="image" src="https://github.com/user-attachments/assets/3b95d6b1-6137-4938-a6b3-d7cba56ed57f" />       |
| `GET /users`           | GET    | Fetch all users                      |         <img width="1190" height="916" alt="image" src="https://github.com/user-attachments/assets/9e0a8295-a816-4205-aa60-0d8c8d451560" />  |
| `GET /users/profile`   | GET    | Get logged-in user's profile         |        <img width="1032" height="664" alt="image" src="https://github.com/user-attachments/assets/34db86cd-b9c7-4f51-bfcd-cd774db3b7c0" />    |
| `PATCH /users/profile` | PATCH  | Update user details                  |   <img width="879" height="667" alt="image" src="https://github.com/user-attachments/assets/83335727-7445-4eb5-ab1b-ee76c049909d" />         |
| `POST /tasks`          | POST   | Create new task                      |       <img width="930" height="680" alt="image" src="https://github.com/user-attachments/assets/47c807f3-ccaa-4ed9-b238-36f712aa1153" />    |
| `GET /tasks`           | GET    | Fetch user's tasks                   |         <img width="949" height="912" alt="image" src="https://github.com/user-attachments/assets/b473cf61-30c5-4cf9-ba0d-05e13cb9cb3f" />   |
| `GET /tasks/:id`       | GET    | Get specific task by ID              |     <img width="998" height="660" alt="image" src="https://github.com/user-attachments/assets/4f4c9c6b-cfb7-485c-915b-a041ebb28595" />      |
| `PATCH /tasks/:id`     | PATCH  | Update task                          |      <img width="792" height="642" alt="image" src="https://github.com/user-attachments/assets/7265d7e4-8d52-4269-b73d-558ae5128a9e" />      |
| `DELETE /tasks/:id`    | DELETE | Delete task                          |     <img width="861" height="635" alt="image" src="https://github.com/user-attachments/assets/c1e9bc38-bd55-48ff-a7cf-be9e23d37557" />       |

---
