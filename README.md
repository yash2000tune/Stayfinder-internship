# 🏡 StayFinder – Airbnb Clone (Internship Project for The Glen)

This is the **core version** of StayFinder, a simplified Airbnb-style web application built as part of the internship selection process at **The Glen**.

## ✨ Project Overview
StayFinder allows users to:
- View a list of property listings
- View individual property details
- Register and log in as users
- (Optional) Post listings as a host

## ⚙️ Tech Stack
- Frontend: React, Tailwind CSS, React Router
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT, bcrypt

## ✅ Features Implemented
- Property listing page with mock data
- User registration & login
- RESTful backend API
- JWT session handling
- Responsive UI

## 💬 Internship Submission Answers
### 1. What tech stack did you choose and why?
I chose the MERN stack (MongoDB, Express.js, React, Node.js) with Tailwind for speed, control, and scalability.

### 2. Are you comfortable building both frontend and backend?
I'm currently more comfortable with frontend development.

### 3. What 2 unique features would you add to improve Airbnb?
1. AI stay recommendations
2. Host trust score based on performance

### 4. How would you secure and scale this app?
Use JWT, bcrypt, input validation, and scale with modular code, pagination, and caching.

## 🚀 Getting Started Locally
1. Clone the repo
2. Run frontend:
   ```bash
   cd client
   npm install
   npm start
   ```
3. Run backend:
   ```bash
   cd ../server
   npm install
   node index.js
   ```
4. Add a `.env` file in `server/`:
   ```
   MONGO_URI=your-mongo-uri
   JWT_SECRET=your-secret
   ```