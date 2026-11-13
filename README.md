# 📸 InstaConnect – Full-Stack Social Media Platform

InstaConnect is a full-stack social media application inspired by Instagram, built using the MERN stack. It allows users to create profiles, share images, interact with posts, and connect through social engagement features.

## 🚀 Overview

InstaConnect provides a platform where users can share visual content, manage their profiles, and interact with other users through likes and comments.

The application uses React.js for the frontend, Node.js and Express.js for backend services, and MongoDB for data management.

## ✨ Key Features

- **User Authentication:** Secure registration and login using JWT authentication.
- **User Profiles:** Create and manage personal profiles.
- **Image Sharing:** Upload and publish image-based posts.
- **Post Management:** Create, view, and manage posts.
- **Like System:** Like and interact with posts.
- **Comment System:** Add and view comments on posts.
- **RESTful APIs:** Backend API integration for application functionality.
- **Responsive UI:** User-friendly interface across different screen sizes.

## 🛠️ Tech Stack

**Frontend**
- React.js
- Tailwind CSS
- JavaScript

**Backend**
- Node.js
- Express.js
- JWT Authentication
- RESTful APIs

**Database**
- MongoDB
- Mongoose

**Media Management**
- Cloudinary

**Development Tools**
- Git
- GitHub
- VS Code
- Postman

## 🏗️ Application Architecture

1. React.js handles frontend rendering and user interactions.
2. Node.js and Express.js manage backend operations and API requests.
3. MongoDB stores user profiles, posts, likes, and comments.
4. JWT handles user authentication and protected routes.
5. Cloudinary manages image uploads and cloud-based media storage.

## 📁 Project Structure

```text
InstaConnect/
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── context/
│       ├── hooks/
│       ├── services/
│       └── assets/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── utils/
│
├── .gitignore
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone YOUR_REPOSITORY_URL
cd InstaConnect
```

### 2. Install Frontend Dependencies

```bash
cd frontend
npm install
```

### 3. Install Backend Dependencies

```bash
cd ../backend
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the backend directory.

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 5. Run the Application

Start the backend:

```bash
cd backend
npm run dev
```

Start the frontend in another terminal:

```bash
cd frontend
npm run dev
```

## 🔐 Security

- JWT-based authentication.
- Protected API routes.
- Environment variables for sensitive credentials.
- Backend validation for application requests.

## 🎯 Project Objectives

- Build a full-stack social media application.
- Implement authentication and user management.
- Understand image upload and cloud storage integration.
- Develop interactive social engagement features.
- Gain practical experience with MERN stack architecture.

## 👨‍💻 Developer

**Samir Khan**

Full Stack Developer | MERN Stack

- Portfolio: https://samirk.site
- GitHub: https://github.com/samirkhan41
- LinkedIn: https://linkedin.com/in/samir-khan-649158358

---

⭐ If you find this project interesting, consider giving it a star!

**Note:** This project is under development. Features and documentation will be updated as development progresses.
