# 🚀 CodeCollab – Real-Time Collaborative Code Editor

**Live Demo:** https://codecollab-5pa3.onrender.com/  
**Tech Stack:** Node.js, Express.js, Socket.IO, React.js, Vite, Monaco Editor, Tailwind CSS

---

## 📌 Overview  
**CodeCollab** is a real-time collaborative code editor that allows multiple users to write and edit code simultaneously in shared rooms.  
The project uses **WebSockets (Socket.IO)** for instant communication and **Monaco Editor** to deliver a VS Code–like coding experience in the browser.

---

## ✨ Features

- ⚡ **Real-time code sync** between all connected users  
- 👥 **Room-based collaboration** using unique room IDs  
- 🧠 **VS Code–like web editor** powered by Monaco Editor  
- 🎨 **Modern UI** built with React + Tailwind CSS  
- 🔄 Automatic broadcasting of code updates  
- 🧩 Clean and modular backend with Express + Socket.IO  

---


---

## 🛠️ Tech Stack

### **Frontend**
- React.js  
- Vite  
- Tailwind CSS  
- @monaco-editor/react  
- Socket.IO Client  

### **Backend**
- Node.js  
- Express.js  
- Socket.IO  

---

## 💡 How Real-Time Sync Works

1. User joins a room (UUID-based)  
2. Editor change triggers a `CODE_CHANGE` event  
3. Socket.IO sends the update to all users in that room  
4. Each client instantly updates their editor content  
➡️ **Smooth, Google Docs-like live collaboration**

---

## 🚀 Getting Started (Run Locally)

### **1. Clone the repository**
```bash
git clone https://github.com/yourusername/CodeCollab.git
cd CodeCollab

```
### **2. Install root dependencies**
```bash
npm install
```

### **3. Install frontend dependencies**
```bash
cd frontend
npm install
```

### **4. Start backend (Server + Socket.IO)**
```bash
npm run dev
```

### **5. Start frontend (React app)**
```bash

cd frontend
npm start

```
### This will open the editor at:

👉 http://localhost:3000






