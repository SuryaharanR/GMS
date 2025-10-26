# 🌐 GMS — Gym Management System

**Live Demo:** [gms-chi.vercel.app](https://gms-chi.vercel.app)

---

## 🧩 Overview
**GMS (Gym Management System)** is a modern web application built to simplify gym operations, manage memberships, and track member activities.  
It provides an intuitive interface for administrators, trainers, and members to efficiently handle registrations, plans, attendance, and payments — all in one platform.

---

## 🚀 Features

- 🧑‍💼 **Admin Panel** — Manage members, trainers, and subscriptions  
- 💪 **Member Dashboard** — View workout plans, payments, and progress  
- 📅 **Attendance Tracking** — Record and monitor daily check-ins  
- 💰 **Plan Management** — Add, edit, and assign membership plans  
- 📊 **Analytics Dashboard** — Visual insights into member data and growth  
- 🔐 **Secure Authentication** — Role-based login and access  
- ☁️ **Deployed on Vercel** — Fast, scalable, and reliable hosting  

---

## 🛠️ Tech Stack

### Frontend:
- React.js (with Hooks & Context API)  
- Tailwind CSS / Material UI  
- Axios  
- React Router  

### Backend:
- Node.js / Express.js  
- MongoDB (Mongoose ORM)  
- JWT Authentication  

### Deployment:
- Frontend: **Vercel**  
- Backend: **Render / Railway / Vercel Functions**

---

## 📦 Installation & Setup

Follow these steps to run the project locally:

```bash
# Clone the repository
git clone https://github.com/<your-username>/gms.git

# Navigate to the project folder
cd gms

# Install dependencies
npm install

# Run the development server
npm start
The app will start running at http://localhost:3000

🔐 Environment Variables
Create a .env file in the root directory and add the following:

bash

REACT_APP_API_URL=<your-backend-api-endpoint>
REACT_APP_AUTH_SECRET=<your-jwt-secret>
If using backend in the same project:

bash

MONGO_URI=<your-mongodb-connection-string>
JWT_SECRET=<your-jwt-secret>
PORT=5000
