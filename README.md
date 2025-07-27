## 🌐 Full Stack Web Application (MEAN Stack)

A robust full-stack web application built with the MEAN stack (MongoDB, Express.js, Angular, Node.js). This project demonstrates a professional-grade, modular development workflow that evolves from a static website to a secure, fully interactive Single Page Application (SPA). It features RESTful APIs, JWT-based authentication, and a clean separation of concerns between backend and frontend, making it ideal for scalable web app development.

### Project Overview

The application simulates a **Trip Management System** where users can browse trips on a public-facing static site and admins can log in via the Angular SPA dashboard to manage trips (create, edit, delete). The backend provides a RESTful API exposing trip data stored in MongoDB. User authentication protects admin features, employing JSON Web Tokens (JWT) and route guards to enforce security.

---

## 🚀 Features

* **Backend:** RESTful API built with Node.js/Express, following MVC architecture for maintainability.
* **Frontend:** Angular 16+ SPA with modular components, services, and route guards for admin dashboard.
* **Database:** MongoDB as the NoSQL data store with Mongoose schemas defining data models and validation.
* **Authentication:** Secure login/logout flow with JWT tokens, stored in localStorage, with backend route protection.
* **Static Site:** Public landing page and trip listings served from a simple static site for SEO and marketing.
* **Modular Git Workflow:** Feature-based branching enables parallel development and easier maintenance.
* **Deployment Ready:** Configuration suitable for cloud deployment, including environment variable management and build optimizations.

---

## 📦 Tech Stack

| Layer          | Technology                     |
| -------------- | ------------------------------ |
| Frontend       | Angular 16+                    |
| Backend        | Node.js, Express               |
| Database       | MongoDB                        |
| ORM/ODM        | Mongoose                       |
| Authentication | JSON Web Tokens (JWT)          |
| Development    | Git, VS Code, Postman, DBeaver |
| Deployment     | Heroku, Netlify, AWS (EC2, S3) |
| Scripting      | PowerShell, Bash CLI           |

---

## 🏗️ Development Phases (Modular Structure)

1. **Static Site & Environment Setup:** Build a simple HTML/CSS landing page; configure Node.js, MongoDB, and tooling.
2. **MVC API:** Create RESTful endpoints with Express for trip CRUD operations.
3. **Dynamic Templates:** Move from static HTML to dynamic server-side rendering with Handlebars and JSON data.
4. **Database Integration:** Define Mongoose schemas, connect to MongoDB, and implement seeding scripts.
5. **API Consumption:** Refactor frontend to consume backend APIs instead of static content.
6. **SPA Admin Panel:** Develop Angular app with components, services, and routing to manage trips dynamically.
7. **Authentication & Security:** Add JWT-based login, secure API routes, and frontend route guards.
8. **Testing & Deployment:** Implement testing with Postman and Angular testing tools, prepare app for deployment.

---

## 🛠️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/fullstack-app.git
cd fullstack-app
```

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

### 4. Configure Environment Variables

Create `.env` files in `backend/` and `frontend/src/environments` with your MongoDB connection URI, JWT secret, and API endpoints.

---

## 🌐 Running the Application

### Start MongoDB (locally or remote)

```bash
mongod
```

### Start Backend Server

```bash
cd backend
npm start
```

API accessible at `http://localhost:3000/api`.

### Start Angular Frontend

```bash
cd frontend
ng serve --open
```

SPA available at `http://localhost:4200`.

---

## 🔐 Authentication

* Secure JWT tokens issued on login.
* Tokens stored in frontend localStorage and sent via HTTP headers.
* Backend middleware verifies tokens on protected routes.
* Angular route guards restrict navigation based on auth status.

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

* API endpoints testable via Postman collections included.
* Angular app includes form validation and unit tests.
* Authentication flows tested with valid/invalid tokens and route access scenarios.

---

## 🚀 Deployment (Optional)

* Backend deployable to Heroku, AWS EC2, or Render.
* Angular SPA hosted on Netlify, Vercel, or AWS S3 + CloudFront for CDN.
* Use MongoDB Atlas for production-grade cloud database.

---

## 📚 Useful Scripts

```bash
# Seed MongoDB with sample trips
npm run seed

# Format code using Prettier
npm run format

# Run lint checks
npm run lint
```

---

## 🙌 Acknowledgments

This project is designed to reflect real-world development workflows and industry best practices for full-stack web apps. It’s an excellent resource for learning modern web development with focus on scalability, security, and maintainability.

---
