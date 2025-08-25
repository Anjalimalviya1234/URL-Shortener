🔗 URL Shortener (MERN Stack)

A simple and efficient URL Shortener Application built with MERN Stack (MongoDB, Express.js, React, Node.js).
This project allows users to shorten long URLs into small, easy-to-share links and redirect them instantly.

🚀 Features

✨ Shorten any valid long URL into a unique short URL

🔗 Redirect short URLs to the original long URLs

📋 Copy shortened URLs to clipboard with one click

🗑️ Delete shortened URLs (optional)

📊 Track total number of shortened URLs (optional)

🎨 Responsive frontend with React + TailwindCSS

🛠️ Tech Stack

Frontend: React.js, Tailwind CSS
Backend: Node.js, Express.js
Database: MongoDB (Mongoose)
Other: Axios, dotenv

📂 Project Structure
url-shortener/
│── backend/        # Node.js + Express backend
│   ├── models/     # Mongoose models
│   ├── routes/     # API routes (shorten, redirect)
│   └── server.js   # Backend entry point
│
│── frontend/       # React frontend
│   ├── src/
│   │   ├── components/
│   │   └── App.js
│   └── package.json
│
│── .gitignore
│── README.MD