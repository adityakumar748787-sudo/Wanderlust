# 🏡 Airbnb Clone (Full Stack Project)

A full-stack web application inspired by Airbnb, built to learn and implement modern web development concepts including backend, database, authentication, and deployment.

---

## 🚀 Live Demo

👉 https://airbnb-clone-6uwd.onrender.com

---

## 🧠 What I Learned

* Building a complete full-stack application from scratch
* RESTful routing using Express.js
* MongoDB database design and integration
* Authentication & authorization
* Image upload using Cloudinary
* Map integration using Mapbox
* Deployment using Render
* Handling real-world errors and debugging

---
## 🛠️ Tech Stack

### Frontend

* EJS (Embedded JavaScript Templates)
* HTML, CSS, Bootstrap

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas

### Other Tools & Services

* Cloudinary (image upload)
* Mapbox (maps & location)
* Passport.js (authentication)
* Render (deployment)

---

## ✨ Features

* 🔐 User authentication (Login/Signup)
* 🏡 Create, edit, and delete property listings
* 📸 Upload and manage listing images
* 📍 Location-based listings using Mapbox
* ⭐ Reviews and ratings system
* 🛡️ Authorization (only owners can edit/delete)
* 🌐 Fully deployed and accessible online

---

## 📂 Project Structure

* `models/` → MongoDB schemas
* `routes/` → Express routes
* `controllers/` → Business logic
* `views/` → EJS templates
* `public/` → Static files (CSS, JS)

---

## ⚙️ Installation (Run Locally)

1. Clone the repository

```bash
git clone https://github.com/0308vivek/Airbnb.git
cd Airbnb
```

2. Install dependencies

```bash
npm install
```

3. Create a `.env` file and add:

```env
MONGO_URL=your_mongodb_url
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_key
CLOUDINARY_SECRET=your_secret
MAPBOX_TOKEN=your_mapbox_token
SESSION_SECRET=your_secret
```

4. Run the app

```bash
node app.js
```

---

## 🌍 Deployment

The application is deployed using Render.

---


