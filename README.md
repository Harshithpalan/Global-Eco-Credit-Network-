# 🌿 Global Eco-Credit Network (GEN)

<div align="center">

![GEN Banner](https://img.shields.io/badge/Global%20Eco--Credit%20Network-GEN-22c55e?style=for-the-badge&logo=leaf&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**A decentralized platform for tracking, verifying, and rewarding eco-friendly actions using AI-powered carbon credit scoring.**

[Features](#-features) • [Tech Stack](#-tech-stack) • [Getting Started](#-getting-started) • [Project Structure](#-project-structure) • [Contributing](#-contributing)

</div>

---

## 🌍 Overview

The **Global Eco-Credit Network (GEN)** is a web application that empowers individuals and organizations to track their environmental impact and earn **Eco-Credits** — a verified digital currency for green actions. Users can log sustainable activities, get them verified by an AI model, and participate in a global community focused on environmental responsibility.

From planting trees to reducing energy consumption, GEN makes it easy to quantify, verify, and be rewarded for your eco-friendly behaviour.

---

## ✨ Features

### 🤖 AI-Powered Verification
- Submit eco-actions (tree planting, recycling, solar usage, etc.) for AI review
- Real-time analysis using Google Gemini AI to verify legitimacy and assign credit values
- Instant feedback with carbon credit score calculation

### 📊 Personal Dashboard
- Live overview of your total Eco-Credits earned
- Track your verified vs. pending actions
- Carbon savings visualized with charts and statistics
- Activity history with timestamps and AI-verified status

### 🏆 Achievements System
- Gamified milestones for your green journey (e.g., "First Green Step", "Carbon Warrior")
- Progress tracking toward next achievement level
- Badges that showcase your environmental commitment

### 🌐 Community Hub
- Global leaderboard of top eco-contributors
- Browse and celebrate community eco-actions
- Real-time updates on community carbon offset totals
- Connect with other environmentally conscious users

### 🔐 Authentication & Data Persistence
- Secure sign-in via Firebase Authentication
- User data and eco-actions stored in Firestore
- Real-time syncing across devices

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | React 18 + Vite |
| **Styling** | Vanilla CSS (custom design system) |
| **Backend/Auth** | Firebase (Authentication + Firestore) |
| **AI Verification** | Google Gemini AI API |
| **Routing** | React Router DOM v6 |
| **Build Tool** | Vite |

---

## 📁 Project Structure

```
Global Eco-Credit Network (GEN)/
├── public/                  # Static assets
├── src/
│   ├── components/
│   │   ├── Hero.jsx         # Landing hero section
│   │   ├── Dashboard.jsx    # Main user dashboard
│   │   ├── Achievements.jsx # Badges & milestones page
│   │   ├── Community.jsx    # Global community feed
│   │   └── Navbar.jsx       # Navigation component
│   ├── lib/
│   │   ├── firebase.js      # Firebase config & initialization
│   │   └── aiService.js     # Gemini AI integration & verification logic
│   ├── App.jsx              # Root component with routing
│   ├── main.jsx             # React entry point
│   └── index.css            # Global styles
├── .gitignore
├── index.html
├── package.json
└── vite.config.js
```

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** v18+ and **npm**
- A **Firebase** project (Authentication + Firestore enabled)
- A **Google Gemini API Key**

### 1. Clone the Repository

```bash
git clone https://github.com/Harshithpalan/Global-Eco-Credit-Network-.git
cd "Global-Eco-Credit-Network-"
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory:

```env
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
VITE_GEMINI_API_KEY=your_gemini_api_key
```

### 4. Run Locally

```bash
npm run dev
```

Visit `http://localhost:5173` in your browser.

### 5. Build for Production

```bash
npm run build
```

---

## 🔥 Firebase Setup

1. Go to [Firebase Console](https://console.firebase.google.com/) and create a new project
2. Enable **Authentication** (Email/Password provider)
3. Create a **Firestore Database** in production mode
4. Add your app's domain to the authorized domains list
5. Copy your Firebase config into the `.env` file

### Firestore Collections

| Collection | Description |
|------------|-------------|
| `users` | User profiles and total Eco-Credit balances |
| `ecoActions` | Submitted and AI-verified eco-actions |
| `achievements` | Unlocked badges per user |

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

1. **Fork** this repository
2. **Create** a feature branch: `git checkout -b feature/your-feature-name`
3. **Commit** your changes: `git commit -m 'Add: your feature description'`
4. **Push** to your branch: `git push origin feature/your-feature-name`
5. **Open** a Pull Request

Please ensure your code follows the existing style and all features work correctly before submitting.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Harshith Palan**

[![GitHub](https://img.shields.io/badge/GitHub-Harshithpalan-181717?style=flat-square&logo=github)](https://github.com/Harshithpalan)

---

<div align="center">

Made with 💚 for a greener planet

*Every eco-action counts. Join the network. Earn your credits. Save the Earth.*

</div>