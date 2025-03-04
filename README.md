# MERN Stack Chat-app with Real-Time Messaging

## 🚀 Overview

This is a full-stack web application built using the MERN (MongoDB, Express, React, Node.js) stack, with real-time messaging capabilities powered by Socket.io. It features user authentication, online status tracking, and a sleek UI using TailwindCSS and Daisy UI. Zustand is used for efficient global state management.

## 🌟 Tech Stack

- **Frontend:** React, TailwindCSS, Daisy UI, Zustand
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Real-Time:** Socket.io
- **Authentication & Authorization:** JWT (JSON Web Token)
- **Image Storage:** Cloudinary

## 🎃 Features

- User authentication & authorization with JWT
- Real-time messaging using Socket.io
- Online user status tracking
- Global state management with Zustand
- Responsive and modern UI with TailwindCSS & Daisy UI
- Play around with themes
- Cloudinary integration for image uploads

## 📦 Installation & Setup

### Prerequisites

Ensure you have the following installed:

- Node.js
- MongoDB (locally or a cloud-based service like MongoDB Atlas)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ashish-kafle14/Realtime-Chatapp.git
cd Realtime-Chatapp
```

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the `server` directory and configure the following environment variables:

```env
PORT=5001
MONGO_URI=.....
JWT_SECRET=........
CLOUDINARY_CLOUD_NAME=.......
CLOUDINARY_API_KEY=......
CLOUDINARY_API_SECRET=.......
```

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
```

### 4️⃣ Build the App

```bash
npm run build
```

### 5️⃣ Start the App

```bash
npm start
```

## ⚡ Usage

1. Register or log in to access the platform.
2. Start real-time messaging with other users.
3. Check online status updates.
4. Customize themes.
5. Upload and share images via Cloudinary.

## 🤝 Contributing

Contributions are welcome! Feel free to submit a PR or open an issue.

## 🌎 Connect

- GitHub: [Ashish Kafle](https://github.com/ashish-kafle14)
