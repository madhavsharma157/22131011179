📄 README.md
markdown
Copy
Edit
# 🔗 AffordMed URL Shortener

A fully functional, responsive, and user-friendly URL shortening web application built with **React (frontend)** and **Node.js + Express (backend)**. This project was developed as part of a **campus hiring frontend evaluation for AffordMed**.

## 🚀 Features

- ✅ Shorten long URLs to custom or random codes
- ⏱️ Set optional expiry time (in minutes)
- 📋 Live display of created short URLs
- 📊 Track total clicks, last access time, and user agent
- 📱 Fully responsive design using Material UI
- 🌐 REST API integration (Express.js backend)
- 🔁 Redirection with click logging
- 📦 Easy to run locally

---

## 🖼️ Demo Screens

| Home (Form + List) | Statistics Page |
|--------------------|-----------------|
| ![Home](./screenshots/home.png) | ![Stats](./screenshots/stats.png) |

---

## 🧑‍💻 Tech Stack

### Frontend
- React.js
- React Router
- Material UI
- Axios

### Backend
- Node.js
- Express.js
- nanoid
- CORS + body-parser

---

## 📦 Installation & Running Locally

### ⚙️ Backend (API Server)

```bash
cd backend
npm install
node index.js
Server runs at: http://localhost:3001

🌐 Frontend (React)
bash
Copy
Edit
# In root folder
npx create-react-app frontend
cd frontend

# Install dependencies
npm install @mui/material @emotion/react @emotion/styled react-router-dom axios

# Replace frontend/src with provided src
# (Copy the "src" folder into frontend)

npm start
Open your browser at: http://localhost:3000

📡 API Endpoints
Method	Endpoint	Description
POST	/shorten	Create a new short URL
GET	/stats	Get stats for all URLs
GET	/:shortcode	Redirect and log access

📂 Folder Structure
css
Copy
Edit
affordmed-url-shortener/
├── backend/
│   └── index.js
├── src/
│   ├── App.js
│   └── components/
│       ├── URLForm.jsx
│       ├── URLList.jsx
│       └── StatsPage.jsx
🎯 Placement Perspective
This project demonstrates:

Component-based architecture

RESTful API integration

Modern responsive UI

Real-world problem solving

Full-stack JavaScript skills

📃 License
MIT License
© 2025 AffordMed Evaluation – Built by Madhav Sharma
