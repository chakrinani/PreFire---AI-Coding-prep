# 🔥 PreFire — AI Coding Prep Platform

PreFire is a **full-stack AI-powered coding preparation platform** that helps students and developers practice coding problems, prepare for interviews, and track progress.  
It combines **MERN stack** with **AI assistance**, real-time coding, and personalized learning.

---

## ✨ Features
- 🧑‍💻 **Code Execution Engine** – Run code directly in the browser  
- 📚 **Problem Sets** – Practice structured coding problems  
- 🔐 **Authentication** – JWT-based secure login/signup  
- 🤖 **AI Assistance** – OpenAI-powered hints and explanations  
- 📊 **Dashboard** – Track progress and submissions  
- 🔄 **Real-Time Updates** – WebSocket-powered live interactions  
- 💳 **Stripe Integration** – Payments & premium features  
- 🔥 **Animations & Effects** – Engaging UI with Tailwind + React  

---

## 🚀 Tech Stack
- **Frontend:** React, Tailwind CSS, React-Scripts  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB Atlas  
- **AI/ML:** OpenAI API  
- **Auth & Security:** JWT, bcrypt  
- **Other:** Firebase, Stripe, ESLint, Prettier  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repo
```bash
git clone https://github.com/chakrinani/PreFire---AI-Coding-prep.git
cd PreFire---AI-Coding-prep
````

### 2️⃣ Backend setup (server)

```bash
cd server
npm install
npm run dev   # or: npm start
```

Runs on 👉 `http://localhost:5001`

### 3️⃣ Frontend setup (client)

Open a new terminal:

```bash
cd client
npm install
npm start
```

Runs on 👉 `http://localhost:3000`

---

## 🔑 Environment Variables

Create `.env` files in **server** and **client**.

### server/.env

```
NODE_ENV=development
PORT=5001
CLIENT_URL=http://localhost:3000
MONGODB_URI=<your_mongodb_atlas_uri>
JWT_SECRET=<your_jwt_secret>
JWT_REFRESH_SECRET=<your_jwt_refresh_secret>
JWT_EXPIRES_IN=7d
OPENAI_API_KEY=<your_openai_key>
ADMIN_EMAIL=admin@prepfire.com
ADMIN_PASSWORD=admin123456
```

### client/.env

```
REACT_APP_API_URL=http://localhost:5001/api
REACT_APP_ENV=development
REACT_APP_GOOGLE_ANALYTICS_ID=<ga_id>
REACT_APP_ENABLE_3D_EFFECTS=true
REACT_APP_ENABLE_PARTICLES=true
REACT_APP_ENABLE_ANIMATIONS=true
REACT_APP_WS_URL=ws://localhost:5001
REACT_APP_STRIPE_PUBLIC_KEY=<stripe_public_key>
REACT_APP_FIREBASE_CONFIG={"apiKey":"<key>","authDomain":"<domain>","projectId":"<id>","storageBucket":"<bucket>","messagingSenderId":"<id>","appId":"<id>","measurementId":"<id>"}
```

---

## 🖥️ Usage

1. Start the **backend** (`npm run dev` inside `server`)
2. Start the **frontend** (`npm start` inside `client`)
3. Open 👉 `http://localhost:3000` in browser

---

## 📌 Contributing

1. Fork the repo
2. Create a new branch (`feature-xyz`)
3. Commit changes
4. Push branch & open a Pull Request

---

## 📜 License

MIT License © 2025 [chakrinani](https://github.com/chakrinani)


