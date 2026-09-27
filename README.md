# 🚀 GenWeb.ai — AI Website Builder

**GenWeb.ai** is a full-stack AI-powered platform that enables users to generate complete, responsive websites instantly by simply describing their idea in plain English. Built with a modern React 19 + Node.js/Express architecture, it combines intelligent prompt-to-code generation with authentication, live previews, and a credit-based Stripe billing system.

🔗 **Live Demo:** [https://ai-website-bulider1-0lvn.onrender.com/](https://ai-website-bulider1-0lvn.onrender.com/)

---

## ✨ Key Features

- 🧠 **Prompt-to-Website Generation:** Generate complete, customizable websites from natural language prompts.
- ⚡ **Interactive Live Preview:** Inspect and test generated layouts directly in the browser.
- 🔐 **Secure Authentication:** Google OAuth via Firebase Authentication + JWT session management.
- 📊 **User Dashboard:** Manage, edit, and organize previously generated websites.
- 💳 **Credit & Subscription System:** Integrated with **Stripe** for purchasing generation credits.
- 🎨 **Immersive 3D & Animated UI:** Built with Tailwind CSS v4, Framer Motion, Three.js, and Vanta.js.

---

## 🛠️ Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | React 19, Vite, Redux Toolkit, React Router v7, Tailwind CSS v4, Framer Motion, Three.js / Vanta.js, Lucide Icons |
| **Backend** | Node.js, Express.js v5, REST API |
| **Database** | MongoDB, Mongoose |
| **Auth & Payments** | Firebase Auth, JSON Web Tokens (JWT), Stripe API (`@stripe/stripe-js` & `stripe`) |
| **Deployment** | Render |

---

## 📁 Project Structure

```text
AI-Website-Builder/
├── client/                 # React 19 + Vite frontend
│   ├── src/
│   ├── package.json
│   └── vite.config.js
├── server/                 # Node.js + Express 5 backend
│   ├── index.js
│   └── package.json
└── README.md
```
## ⚙️ Installation & Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/UtkarshDashora/AI-website-bulider.git
cd AI-website-bulider
```
### 2. Setup the Backend (server)

```bash
cd server
npm install
```

Create a .env file inside the server/ directory:
```evn
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
AI_API_KEY=your_ai_provider_api_key
```
Start the backend server:
```bash
npm run dev
```
### 3. Setup the Frontend (client)

Open a new terminal:
```bash
cd client
npm install
npm run dev
```
The application will be available at:
```
http://localhost:5173
```
