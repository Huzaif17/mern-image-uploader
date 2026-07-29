# 📸 MERN Image Uploader

A full-stack image uploading application built with the **MERN Stack**. Users can upload images through a modern React interface, where the images are stored securely on **ImageKit Cloud** while image metadata is saved in **MongoDB**. The application follows a clean and modular architecture with a RESTful Express.js backend.

---

## 🚀 Features

* 📤 Upload images from the browser
* ☁️ Store images securely using ImageKit
* 🗄️ Save image information in MongoDB
* ⚡ Fast frontend built with React + Vite
* 🔗 RESTful API using Express.js
* 🔒 Secure configuration with environment variables
* 📱 Responsive and user-friendly interface

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* JavaScript
* HTML
* CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Cloud Storage

* ImageKit

### Tools

* Git
* GitHub
* npm

---

## 📂 Project Structure

```text
mern-image-uploader/
│
├── backend/
│   ├── server.js
│   ├── app.js
│   ├── models/
│   ├── routes/
│   ├── storage/
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── screenshots/
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Huzaif17/mern-image-uploader.git
```

### 2. Navigate into the project

```bash
cd mern-image-uploader
```

### 3. Install backend dependencies

```bash
cd backend
npm install
```

### 4. Install frontend dependencies

```bash
cd ../frontend
npm install
```

---

## ▶️ Running the Project

### Start the Backend

```bash
cd backend
npm run dev
```

### Start the Frontend

```bash
cd frontend
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file inside the **backend** folder and add the following:

```env
PORT=3000

MONGODB_URI=your_mongodb_connection_string

IMAGEKIT_PRIVATE_KEY=your_private_key
```

> **Note:** Never commit your `.env` file to GitHub.

---

## 📚 What I Learned

* Building a full-stack MERN application
* Creating RESTful APIs with Express.js
* Connecting Node.js with MongoDB using Mongoose
* Uploading images to ImageKit Cloud
* Managing environment variables securely
* Organizing a scalable backend structure
* Using Git and GitHub for version control

---

## 🔮 Future Improvements

* Drag-and-drop image upload
* Image gallery with search
* Image deletion
* Image compression
* Pagination
* Dark mode
* Deployment on Vercel and Render

---

## 👨‍💻 Author

**Huzaif Sayed**

If you found this project helpful, feel free to ⭐ the repository.
