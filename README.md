# 🏡 Home Haven

**Home Haven** is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application that allows users to list rental places for booking and enables other users to explore and book those places with ease.

## 🌐 Live Demo

[Click here to view the live site](https://home-haven-nu.vercel.app/) <!-- Replace '#' with your live URL -->

---

## 📌 Features

- 🔐 User authentication (Sign up, Login, Logout)
- 🏠 List a place with title, description, price, location, and images
- 📅 Book a listed place for specific dates
- 🧾 View booking history
- 🖼️ Image upload and preview functionality
- 🧭 Mobile-responsive UI for a smooth experience across devices

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS (or Bootstrap/Material UI)
- Axios

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)

### Other Tools
- JWT (Authentication)
- Cloudinary or Multer (Image Uploads)
- Dotenv (Environment Variables)

---

## 🧑‍💻 Getting Started

Follow these instructions to set up the project on your local machine.

### ✅ Prerequisites

- Node.js and npm installed
- MongoDB installed locally or have a MongoDB Atlas URI

---

## 🚀 Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/22rahulrai/Home-Haven.git
cd Home-Haven
```

## Setup Backend (Server)

```bash
cd server
npm install
```

Create a .env file in the server directory and add the following:

```bash
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

## Start the backend server:

```bash
npm run dev
```

## Setup Frontend (Client)

```bash
cd ../client
npm install
npm start
```

## 📁 Project Structure



## 👨‍💻 Contributing

Contributions are welcome! Here’s how you can help:

1. Fork the repository

2. Create your feature branch:
```bash
git checkout -b feature/feature-name
```
3. Commit your changes:
```bash
git commit -m "Add some feature"
```
4. Push to the branch:
```bash
git push origin feature/feature-name
```

5. Open a pull request


