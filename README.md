![logo](https://github.com/sahilatahar/Code-Sync/assets/100127570/d1ff7f52-a692-4d51-b281-358aeab9156e)

A collaborative, real-time code editor where users can seamlessly code together. It provides a platform for multiple users to enter a room, share a unique room ID, and collaborate on code simultaneously.

![GitHub contributors](https://img.shields.io/github/contributors/sahilatahar/Code-Sync?style=for-the-badge&color=48bf21)
![GitHub Repo stars](https://img.shields.io/github/stars/sahilatahar/Code-Sync?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/sahilatahar/Code-Sync?style=for-the-badge&color=d7af2d)
![GitHub pull requests](https://img.shields.io/github/issues-pr/sahilatahar/Code-Sync?style=for-the-badge&color=f47373)
![GitHub License](https://img.shields.io/github/license/sahilatahar/Code-Sync?style=for-the-badge&color=e67234)
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fsahilatahar%2FCode-Sync&label=Repo%20Views&countColor=%2337d67a&labelStyle=upper)

## 🔮 Features

- 💻 Real-time collaboration on code editing across multiple files
- 📁 Create, open, edit, save, delete, and organize files and folders
- 💾 Option to download the entire codebase as a zip file
- 🚀 Unique room generation with room ID for collaboration
- 🌍 Comprehensive language support for versatile programming
- 🌈 Syntax highlighting for various file types with auto-language detection
- 🚀 Code Execution: Users can execute the code directly within the collaboration environment
- ⏱️ Instant updates and synchronization of code changes across all files and folders
- 📣 Notifications for user join and leave events
- 👥 User presence list with online/offline status indicators
- 💬 Real-time group chatting functionality
- 🎩 Real-time tooltip displaying users currently editing
- 💡 Auto suggestion based on programming language
- 🔠 Option to change font size and font family
- 🎨 Multiple themes for personalized coding experience
- 🎨 Collaborative Drawing: Enable users to draw and sketch collaboratively in real-time
- 🤖 Copilot: An AI-powered assistant that generates code, allowing you to insert, copy, or replace content seamlessly within your files.

## 🚀 Live Preview

You can view the live preview of the project [here](https://code-sync-live.vercel.app/).

## 💻 Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![ExpressJS](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![Socket io](https://img.shields.io/badge/Socket.io-ffffff?style=for-the-badge)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

## ⚙️ Installation

### Method 1: Manual Installation

1. **Fork this repository:** Click the Fork button located in the top-right corner of this page.
2. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/Code-Sync.git
   ```
3. **Create .env file:**
   Inside the client and server directories create `.env` and set:

   Frontend:

   ```bash
   VITE_BACKEND_URL=<your_server_url>
   ```

   Backend:

   ```bash
   PORT=3000
   ```

4. **Install dependencies:**
   ```bash
   npm install     # Run in both client and server directories
   ```
5. **Start the servers:**
   Frontend:
   ```bash
   cd client
   npm run dev
   ```
   Backend:
   ```bash
   cd server
   npm run dev
   ```
6. **Access the application:**
   ```bash
   http://localhost:5173/
   ```
### 🎥 Need help with the setup?
👉 Watch [this video](https://youtu.be/zVHwOmU0aqo) for a step-by-step guide.
### Method 2: Docker Installation

1. **Install Docker Desktop:**

   - Download and install **Docker Desktop** from [Docker’s official website](https://www.docker.com/products/docker-desktop/).
   - Verify installation:
     ```bash
     docker --version
     ```

2. **Pull Docker Images:**

   ```bash
   # Pull Backend Image
   docker pull sahilatahar/code-sync-server:latest

   # Pull Frontend Image
   docker pull sahilatahar/code-sync-client:latest
   ```

3. **Run Docker Containers:**

   ```bash
   # Run Backend Container (Port 3000)
   docker run -d -p 3000:3000 --name code-sync-server sahilatahar/code-sync-server:latest

   # Run Frontend Container (Port 5173)
   docker run -d -p 5173:5173 --name code-sync-client sahilatahar/code-sync-client:latest
   ```

4. **Access the application:**
   ```bash
   http://localhost:5173/
   ```


