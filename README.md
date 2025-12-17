🛒 E-Commerce Website (MERN Stack)

A full-stack E-Commerce web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).
The project includes user authentication, product browsing, cart management, and an admin panel for product management.

🚀 Features

User Signup & Login with JWT authentication

Dynamic product listing fetched from backend APIs

Add to Cart / Remove from Cart functionality

Admin Panel for adding and removing products

Image upload for products using Multer

Responsive UI with CSS Media Queries

Secure password handling using bcrypt

🧰 Tech Stack

Frontend:

React.js

Context API

React Router

CSS (Media Queries)

Backend:

Node.js

Express.js

RESTful APIs

JWT Authentication

Multer

Database:

MongoDB Atlas

Deployment:

Frontend: Vercel

Backend: Render / Heroku

⚙️ Project Structure
/frontend   → React UI
/backend    → Node.js + Express APIs
/admin      → Admin Panel for product management

🔐 Authentication Flow

Users can sign up and log in

JWT token is generated on login/signup

Token is stored on client side and sent with protected requests

Backend middleware verifies token for secure routes

📦 Installation & Setup
Clone the repository
git clone https://github.com/your-username/E-Commerce-Website.git

Backend Setup
cd backend
npm install
npm start

Frontend Setup
cd frontend
npm install
npm start

🧑‍💻 Admin Panel

Add new products with image upload

View all products

Delete products

Changes reflect instantly on user side

📌 Learning Outcome

This project helped me gain hands-on experience in:

Full-stack MERN development

REST API design

Authentication & authorization

Database modeling with MongoDB

Frontend-backend integration

📄 License

This project is open-source and available for learning and educational purposes.
