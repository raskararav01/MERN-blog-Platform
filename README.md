# MERN-blog-Platform
A full-stack blog platform built with the MERN stack, featuring user authentication, blog creation and management, RESTful APIs, and a responsive frontend.

# 📝 MERN Blog Platform

A full-stack blog platform developed using the **MERN Stack — MongoDB, Express.js, React.js, and Node.js**.

The project demonstrates full-stack web development concepts including RESTful APIs, database integration, user authentication, CRUD operations, and responsive frontend development.

---

## 🚀 Features

* 🔐 User authentication and authorization
* 👤 User management
* 📝 Create, read, update and delete blog posts
* 📚 Blog listing and individual blog pages
* 🔎 API-based communication between frontend and backend
* 🗄️ MongoDB database integration
* ⚡ RESTful backend APIs
* 📱 Responsive user interface
* 🔒 Environment-variable based configuration
* 🧩 Modular frontend and backend architecture

---

## 🛠️ Tech Stack

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Vite

### Backend

* Node.js
* Express.js
* REST API

### Database

* MongoDB
* MongoDB Atlas

### Development Tools

* Git
* GitHub
* VS Code
* npm

---

## 📂 Project Structure

```text
mern-blog-platform/
│
├── backend/
│   ├── config/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── index.js
│   ├── package.json
│   ├── package-lock.json
│   ├── .env.example
│   └── .gitignore
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   ├── package-lock.json
│   └── .gitignore
│
├── README.md
└── .gitignore
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/mern-blog-platform.git
```

```bash
cd mern-blog-platform
```

---

### 2. Install backend dependencies

```bash
cd backend
npm install
```

---

### 3. Configure environment variables

Create a `.env` file inside the `backend` directory.

```env
MONGODB_USERNAME=your_username
MONGODB_PASSWORD=your_password
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

### 4. Start the backend

```bash
npm start
```

or, if the project uses a development script:

```bash
npm run dev
```

---

### 5. Install frontend dependencies

Open a new terminal:

```bash
cd frontend
npm install
```

---

### 6. Start the frontend

```bash
npm run dev
```

The application will then be available through the local development URL provided by Vite.

---

## 🔑 Environment Variables

The project uses environment variables to protect configuration and credentials.

Create your own `.env` file based on `.env.example`.

Example:

```env
MONGODB_USERNAME=your_username
MONGODB_PASSWORD=your_password
MONGODB_URI=your_mongodb_connection_string
PORT=5000

Example:
screenshots/
├── home.png
├── login.png
├── register.png
├── blog.png
└── dashboard.png

## 🧠 What I Learned
Through this project, I gained practical experience with:

* Building full-stack applications using the MERN stack
* Designing and consuming REST APIs
* Connecting Node.js applications with MongoDB
* Implementing CRUD operations
* Managing frontend and backend communication
* Working with environment variables
* Structuring a scalable web application
* Using Git and GitHub for version control

## 🔮 Future Improvements
Planned improvements include:

* JWT-based authentication
* Role-based authorization
* Rich text editor for blog creation
* Image upload functionality
* Search and filtering
* Pagination
* User profiles
* Comments and likes
* Admin dashboard
* Cloud deployment
* Improved UI/UX
