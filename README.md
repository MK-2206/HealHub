<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://med-pal.vercel.app">
    <img src="https://ik.imagekit.io/spursy/MedPal/apple-touch-icon.png?updatedAt=1681674938894" alt="Logo" width="80" height="80">
  </a>
  <h1 align="center">HealHub</h3>
</div>



HealHub is a personal medical tracker that lets users manage their well-being online by recording and monitoring health data. It empowers users with full control over their medical information.

--

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

<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/dc6c7966-ad3f-409f-b2de-e17b1450b8e9" />
<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/c2386db0-eea5-4b45-8863-623074a6d015" />
<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/26288997-3c3f-4a61-ae69-123e5df82d62" />
<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/90e6c9c2-85db-4741-882a-dae8e0f98ef9" />
<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/9b250ac4-d9b6-44ba-af96-b674717ef3fd" />
<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/870a94c1-2de9-4a80-a887-ef75f477c663" />
<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/3fec31d8-9848-4754-916c-c1ddb24a1463" />
<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/ce6080b7-c125-4b51-bb30-21c793f967ea" />
<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/652d09ce-7b4f-4d50-9943-c78c8f96eee7" />
<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/bb8cd882-a88f-42af-979c-9b5b3de1be10" />
<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/a558a365-2838-4749-8238-42d35877ed69" />

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
