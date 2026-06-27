# 🚀 ByteBattle – AI-Powered Collaborative Coding Platform  

[![Node.js](https://img.shields.io/badge/Node.js-Express-blue?logo=node.js)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-green?logo=mongodb)](https://www.mongodb.com/)
[![Socket.io](https://img.shields.io/badge/RealTime-Socket.IO-black?logo=socket.io)](https://socket.io/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

🎥 **Demo Video (in case live site is down):** 

> ⚠️ *Note: Solution videos currently available for selected problems only:*
> - Remove Duplicates from Sorted Array  
> - 1st Largest Element of Array  
> - Longest Common Subsequence  
> - Number of Islands  
> - Sum of All Elements of Array  
> - Climbing Stairs  

---

## 🧩 Overview  

**ByteBattle** is a full-stack, production-grade online coding platform designed for **Data Structures and Algorithms (DSA) practice**, **collaborative problem-solving**, **AI-powered code assistance**, and **competitive contests**.  
It enables learners and developers to code, collaborate, and compete in real time — with secure authentication and scalable architecture.

---

## ⚡ Key Features  

### 🧠 1. DSA Practice Platform  
- Monaco Editor for in-browser coding.  
- Language Support: **Java, C++, JavaScript**  
- Built-in test case validation and result tracking.  
- Unlock **solution videos** and explanations post-problem solving.  

### 👯 2. Collaborative Coding  
- Real-time shared editor using **Socket.IO**.  
- **Live cursor tracking** and multi-user editing.  
- Host controls submissions and language changes.  
- Guest and authenticated modes supported.  

### 🤖 3. AI Code Assistant (Gemini 2.5 Flash)  
- Context-aware, **problem-specific AI assistant**.  
- Avoids irrelevant or generic responses.  
- Integrated directly into the problem page.  

### ⏱️ 4. Timed Coding Competitions  
- Dynamic contest environment with timers.  
- Real-time leaderboard updates and scoring.  
- Ranking system inspired by **Dragon Ball Z** tiers.  
- Question weights scale by difficulty.  

### 💬 5. Community Chat Support  
- Public chatroom using **Socket.IO** channels.  
- Peer discussion and mentor support.  
- Optional topic/difficulty-based channels.  

### 🔐 6. Secure Authentication  
- **JWT tokens** with persistent sessions.  
- **Magic Link login** via **NodeMailer**.  
- **Google One Tap OAuth** integration.  
- **Redis blocklist** for secure logout and session control.  

### 🧑‍💻 7. User Profile  
- Heatmap for coding consistency.  
- Problem-solving and login streak analytics.  
- Contest ratings based on Dragon Ball Z theme.  

### 🛠️ 8. Admin Panel  
- Add, edit, or delete problems.  
- Upload video solutions.  
- Manage contests and problem metadata.  

---

## 🧰 Technology Stack  

| Component | Technology |
|------------|-------------|
| **Frontend** | React.js, Tailwind CSS, DaisyUI, Lucide Icons |
| **Code Editor** | Monaco Editor |
| **Code Execution** | Judge0 API |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **AI Assistant** | Gemini 2.5 Flash |
| **Authentication** | JWT, Redis, NodeMailer, Google One Tap SDK |
| **Real-time Communication** | Socket.IO |
| **Media/CDN** | Cloudinary |
| **Deployment** |   AWS (EC2) using Ngnix for reverse proxy |

---

### 💻 Frontend  
- Built using **React.js** with responsive UI via **Tailwind CSS**.  
- Integrated **Monaco Editor** for real-time code writing.  
- Supports **language toggle** and live updates.

### 🔐 Authentication Module  
- Session handling via **JWT**.  
- **Redis** used for token invalidation on logout.  
- **Magic link login** using **NodeMailer**.  
- **Google One Tap SDK** for quick OAuth.

### ⚙️ DSA Module  
- Problem statements, test cases, and submissions stored in **MongoDB**.  
- Backend executes code and validates results via **Judge0 API**.  

### 🤝 Collaborative Coding  
- **Socket.IO** rooms for real-time collaboration.  
- Live cursor tracking and user presence management.  

### 🧩 AI Assistant  
- Integrated Gemini 2.5 Flash for focused DSA-related code guidance.  
- Context-sensitive responses inside problem interface.  

### 🧮 Competition Module  
- Live contests with countdowns, difficulty-based scoring, and leaderboards.  

### 💬 Community Chat  
- **Socket.IO channels** for real-time public chatrooms and support.  

---

## 🔮 Future Enhancements  
- User-hosted contests.  
- Mobile-optimized coding experience.  
- In-depth user analytics and badges.  
- Payment gateway for premium features.  

---

## 🏁 Summary  

**ByteBattle** merges **modern web technologies, AI assistance, and real-time collaboration** into a powerful coding practice ecosystem.  
It’s built to help learners and professionals alike improve problem-solving skills, collaborate effectively, and compete in a gamified, interactive environment.

---

## 💻 Project Links  
- **GitHub Repository:** [https://github.com/WR-Shashank/ByteBattle.0]   

---

### 🧑‍🎓 Author  
**Shashank**  
B.Tech IT @ IIIT Bhopal  

