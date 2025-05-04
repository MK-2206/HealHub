<!-- PROJECT LOGO -->
<div align="center">
  <a href="https://healhub.vercel.app">
    <img src="your_logo_or_icon_link_here" alt="Logo" width="80" height="80">
  </a>
  <h1 align="center">HealHub</h1>
</div>

HealHub is a personal medical tracker that lets users manage their well-being online by recording and monitoring health data. It empowers users with full control over their medical information.

> 🚀 Live site: [https://healhub.vercel.app](https://healhub.vercel.app)  
> 🛠️ Backend API: [https://healhub-backend.onrender.com/api](https://healhub-backend.onrender.com/api)

---

## 📌 Features

- 🧭 Central dashboard for vital data and app modules  
- 📊 Analyze lab vitals like BP, sugar, and hemoglobin in charts  
- 💊 Manage medicines and set daily intake reminders  
- 📁 Upload and access medical reports securely  
- 📅 Schedule and manage doctor appointments  
- 📍 Locate nearby doctors using geolocation  
- 📱 Fully responsive for mobile and desktop use

---

## 🖼️ Screenshots

> _Replace these links with your own screenshots later:_

- **Dashboard**  
  ![](your_screenshot_links/Dashboard.png)
- **Vitals Chart**  
  ![](your_screenshot_links/Charts.png)
- **Doctor Search**  
  ![](your_screenshot_links/DoctorSearch.png)

---

## 🧱 Tech Stack

| Layer      | Technology                          |
|------------|--------------------------------------|
| Frontend   | React.js, Bootstrap                  |
| Backend    | Node.js, Express.js                  |
| Database   | MongoDB (Atlas)                      |
| Auth       | JWT                                  |
| Hosting    | Vercel (Frontend), Render (Backend)  |
| Tools      | Postman, Google Cloud, VS Code       |

---

## ⚙️ Getting Started Locally

### 1. Clone the repository

```bash
git clone https://github.com/MK-2206/HealHub.git
cd HealHub
##2. Install dependencies
bash
Copy
Edit
# Frontend
cd client
npm install

# Backend
cd ../server
npm install

MONGODB_URI=your_mongo_uri
PORT=5000
SECRET=your_jwt_secret

RUN THE APP
# Terminal 1: Backend
cd server
npm run dev

# Terminal 2: Frontend
cd client
npm start
