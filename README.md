# 🏨 MoeTours

This is a complete **Hotel Booking System** built with the **MERN Stack** – MongoDB, Express.js, React.js, and Node.js. The app includes a **fully featured Admin Dashboard**, **JWT-based authentication**, and **Postman-tested APIs** for managing hotels and reservations. The frontend is built with **React**, **Context API**, **React Calendar**, and custom components.


## Features

### ✅ Backend Features
- MongoDB database integration
- Node.js + Express.js REST APIs
- Full CRUD operations (Create, Read, Update, Delete)
- JWT Authentication & Authorization (Admin/User)
- Role-based access (Admin protected routes)
- Tested with Postman

### Frontend Features
- React app with Context API
- React Calendar-based booking system
- Custom hooks for data fetching
- Mobile-responsive UI with CSS
- Search filters, sliders, and hotel lists

---

## Tech Stack

| Layer       | Tech                                     |
|------------|------------------------------------------|
| Frontend    | React.js, Context API, React Router, HTML/CSS, React Calendar |
| Backend     | Node.js, Express.js, MongoDB, Mongoose  |
| Auth        | JWT (JSON Web Tokens)                   |
| Tools       | Postman, MongoDB Compass                |

---

## UI Preview

### Admin Panel (Backend)

![Admin Login]![image](https://github.com/user-attachments/assets/0ece160f-2069-4e22-b0be-8db720381d6b)
![CRUD in Postman]![WhatsApp Image 2025-04-29 at 20 25 22_8c0c3b93](https://github.com/user-attachments/assets/bf2f2311-7419-40f9-90ba-527ea2e909dc)
![Admin Pages]![image](https://github.com/user-attachments/assets/6766673b-7d9e-42d9-9429-ca10ecba42ef)
![MongoDB Models]![image](https://github.com/user-attachments/assets/59c69a9c-b556-4852-84e3-84934bb44c06)


---

### Frontend (User Booking System)

![Home Page]![image](https://github.com/user-attachments/assets/ba6a12d3-01ed-42fa-8bf5-6653541e8f79)
![Hotel Page]![image](https://github.com/user-attachments/assets/1b3d8945-d2c8-41d2-b4b6-3ba76cdc72ee)
![Reservation Page]![image](https://github.com/user-attachments/assets/d53ef494-be13-4aad-8578-e60f005fcc8b)
![All Hotels]![image](https://github.com/user-attachments/assets/3b342394-7bac-4e1f-9bcb-91e30095abea)
![Footer]![image](https://github.com/user-attachments/assets/56900605-d075-4e9f-94bb-4d64e6fc67f1)

## API Endpoints (CRUD)

| Method | Endpoint              | Description                  |
|--------|-----------------------|------------------------------|
| POST   | `/api/hotels`         | Add a new hotel              |
| GET    | `/api/hotels`         | List all hotels              |
| GET    | `/api/hotels/:id`     | Get single hotel details     |
| PUT    | `/api/hotels/:id`     | Update hotel info            |
| DELETE | `/api/hotels/:id`     | Delete hotel                 |
| POST   | `/api/auth/register`  | Register user                |
| POST   | `/api/auth/login`     | Login and receive JWT token  |
