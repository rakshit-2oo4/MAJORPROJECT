# 🏠 Wanderlust

A full-featured **Airbnb clone** built using **Node.js, Express, MongoDB, EJS**, and modern web development practices. This project allows users to **register, log in, create listings, browse properties, and book stays** — all with server-rendered pages, cloud image uploads, secure authentication, and more.

---
### 🔗 Link --> https://majorproject-n6b4.onrender.com

---
## 📖 Overview

This project simulates the essential operations of Airbnb:

- User registration & login  
- Posting new listings (by hosts)  
- Viewing and booking rental properties  
- Secure form validation  
- Cloud-based image uploads  
- Flash messaging and session management  

It is a complete full-stack application using **server-side rendering** via EJS and **MongoDB** for data storage.

---

## 🚀 Features

- 🔐 User authentication (Passport.js)  
- 📸 Image uploads using **Multer + Cloudinary**  
- 📋 Listing CRUD operations (Create, Read, Update, Delete)  
- 🧾 Input validation with Joi  
- 💬 Flash messaging system  
- 🧠 Middleware-driven architecture  
- 🗂 Session storage using **connect-mongo**  
- 🌐 Server-side views with EJS and layouts (ejs-mate)  
- 📱 Fully responsive using **Bootstrap**

---

## 🛠 Tech Stack

**Frontend:**  
- HTML, CSS, JavaScript  
- Bootstrap 5  
- EJS + EJS-Mate  

**Backend:**  
- Node.js  
- Express.js  

**Database:**  
- MongoDB  
- Mongoose  

**Authentication & Security:**  
- Passport.js (Local Strategy)  
- Passport-Local-Mongoose  
- Express-Session  
- Cookie-Parser  
- Connect-Mongo  
- Joi  

**Utilities:**  
- Multer  
- Cloudinary  
- Multer-Storage-Cloudinary  
- dotenv  
- Connect-Flash  
- Method-Override  

---

## ⚙️ Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/majorproject.git
cd majorproject

# 2. Install all dependencies
npm install

# 3. Create a .env file in the root directory with these contents:
cat <<EOL > .env
DATABASE_URL=mongodb+srv://<username>:<password>@cluster.mongodb.net/airbnb-clone
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
SECRET=your_session_secret
EOL

# (Replace placeholders with your actual credentials!)

# 4. Start the app
node index.js

# The app will run at http://localhost:3000

# For development, run with nodemon:
# nodemon index.js
