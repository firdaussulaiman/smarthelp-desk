# smarthelp-desk
SmartHelp Desk is a modern, modular ticketing system for internal IT support and service desk operations. The application is built with a React frontend (using Vite), a Node.js + Express backend, and a MongoDB Atlas database.

This project is structured for scalable growth, with planned integration of:

🔐 Microsoft Entra ID (for secure Microsoft login)

📬 Microsoft Graph API (to send Outlook emails and Teams alerts)

☁️ Azure deployment (via Terraform and CI/CD pipelines)

It’s designed to mimic real-world enterprise infrastructure, making it suitable for learning full-stack app development and cloud engineering practices.

# 🎫 SmartHelp Desk

A custom-built full-stack ticketing system designed for service desk use. Built with React (Vite) and Express.js, backed by MongoDB Atlas, and structured for Microsoft 365 and Azure integration.

---

## 🚀 Features

- 📝 Ticket submission form (name, email, issue)
- 📬 API to store tickets in MongoDB
- 🔐 Designed for Microsoft Entra ID login (future)
- 📧 Microsoft Graph API email + Teams alerts (planned)
- ☁️ Deployable on Azure using Terraform + CI/CD

---

## 🛠️ Tech Stack

| Layer        | Stack                          |
|--------------|-------------------------------|
| Frontend     | React + Vite                  |
| Backend      | Node.js + Express             |
| Database     | MongoDB Atlas (Cloud-hosted)  |
| Dev Tools    | GitHub, VS Code, nodemon      |
| Future       | Azure App Service, Graph API  |

---

## 📦 Project Setup

### 🔧 Backend

```bash
cd backend
npm install
npx nodemon server.js

