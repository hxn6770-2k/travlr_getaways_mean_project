## 🌐 Full Stack Web Application (MEAN Stack)

A robust full-stack web application built with the MEAN stack (MongoDB, Express.js, Angular, Node.js). Structured into modular development phases, the project evolves from a basic static site to a secure, dynamic Single Page Application (SPA) with RESTful APIs and MongoDB.

---

## 🚀 Features

- RESTful API using Node.js/Express with MVC structure
- Angular-based admin SPA for trip management
- MongoDB with Mongoose for data modeling
- JWT-based authentication & authorization
- Route protection via Express middleware
- Static landing site served from `public/`
- Modular Git branching strategy by feature/module

---

## 📦 Tech Stack

| Layer          | Technology        |
|----------------|-------------------|
| Frontend       | Angular 16+       |
| Backend        | Node.js, Express  |
| Database       | MongoDB           |
| Authentication | JSON Web Tokens   |
| Tools          | Git, VS Code, Postman, DBeaver |
| DevOps         | PowerShell, CLI   |

---

## 🛠️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/fullstack-app.git
cd fullstack-app
````

### 2. Install Backend Dependencies

```bash
cd backend
npm install
```

### 3. Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

---

## 🌐 Running the Application

### Start MongoDB (locally)

```bash
mongod
```

Ensure MongoDB is running on its default port (`27017`).

### Start Backend Server

```bash
cd backend
npm start
```

API will be accessible at `http://localhost:3000/api`.

### Start Angular Frontend

```bash
cd frontend
ng serve --open
```

SPA will open at `http://localhost:4200`.

---

## 🔐 Authentication

* JWT-based auth for secure backend APIs
* Angular stores token in `localStorage`
* Protected routes using Express middleware

---

## 📤 Sample API Endpoints

| Method | Endpoint         | Description       |
| ------ | ---------------- | ----------------- |
| GET    | `/api/trips`     | Get all trips     |
| POST   | `/api/trips`     | Create a new trip |
| PUT    | `/api/trips/:id` | Update a trip     |
| DELETE | `/api/trips/:id` | Delete a trip     |

---

## 🧪 Testing

* Use Postman for manual API testing
* Angular components tested with form validation
* Auth routes tested with/without valid tokens

---

## 🚀 Deployment (Optional)

* **Backend**: Heroku, AWS EC2, Render
* **Frontend**: Netlify, Vercel, or AWS S3 + CloudFront
* **Database**: MongoDB Atlas for production hosting

---

## 📚 Useful Scripts

```bash
# Seed MongoDB with initial data
npm run seed

# Format code
npm run format

# Lint check
npm run lint
```

---

## 🙌 Acknowledgments

This project follows modern, scalable patterns commonly used in industry environments. It's an excellent learning and launching point for developers exploring full-stack web application architecture with real-world practices.

---

