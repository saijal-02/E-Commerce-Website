🛒 E-Commerce Website (MERN Stack)

A full-stack E-Commerce web application built using the MERN stack — MongoDB, Express.js, React.js, and Node.js.
The project supports user authentication, product browsing, cart management, and an admin panel for managing products.

🚀 Features

User Signup & Login using JWT authentication

Dynamic product fetching from backend using REST APIs

Add to Cart / Remove from Cart functionality

Admin Panel for adding and deleting products

Product image upload using Multer

Responsive UI using CSS Media Queries

Global state management using React Context API

🧰 Tech Stack
Frontend

React.js

Context API

React Router

CSS (Media Queries)

Backend

Node.js

Express.js

RESTful APIs

JWT Authentication

Multer (Image Upload)

Database

MongoDB Atlas

📁 Project Structure
E-Commerce-Website/

├── frontend/        → User-facing React application

├── admin/           → Admin panel for product management

├── backend/         → Node.js + Express backend APIs

🔐 Authentication Flow

Users can sign up or log in

Backend generates a JWT token

Token is stored in browser localStorage

Token is sent in request headers for protected routes

Backend middleware verifies the token before allowing access

🧑‍💼 Admin Panel

Add new products with image upload

View all products

Remove products

Changes reflect instantly on the frontend

📦 Installation & Setup
Clone Repository
git clone https://github.com/saijal-02/E-Commerce-Website.git

Backend Setup
cd backend
npm install
npm start

Frontend Setup
cd frontend
npm install
npm start

Admin Panel Setup
cd admin
npm install
npm start

📌 Learning Outcomes

End-to-end full-stack development using MERN

REST API design and backend integration

JWT-based authentication and middleware usage

MongoDB schema design and data handling

React state management using Context API

Building responsive and scalable web applications

📄 License

This project is open-source and created for learning and educational purposes.
