# 🚀 DevOps Project Guide – Application Identification Cheat Sheet

![DevOps](https://img.shields.io/badge/DevOps-Learning-blue?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-Basics-2496ED?style=for-the-badge&logo=docker)
![Beginner Friendly](https://img.shields.io/badge/Level-Beginner-green?style=for-the-badge)

## 🎯 About This Repository
This repo helps beginners understand:
✨ How to identify different types of applications  
✨ How to decide what Dockerfile to write  
✨ How real-world projects are structured  
✨ DevOps thinking mindset (VERY IMPORTANT 🚀)

## 🧠 Golden Rule of DevOps Thinking
Code Copy → Install → Build → Run → Serve

# 🔍 Application Type Identification Guide

## 🟡 Node.js (Backend API)
Clues:
- package.json
- server.js / app.js
- npm start
- .env file

📌 Meaning:
👉 Backend API / Server application

## 🔵 React (Frontend UI)
Clues:
- src/
- public/
- App.js / App.jsx
- react-scripts

📌 Meaning:
👉 Web UI Application (Frontend)

## 🟣 Next.js (Full Stack React)
Clues:
- pages/ or app/
- next.config.js
- package.json → "next"

📌 Meaning:
👉 SSR + Frontend + Backend hybrid

## 🟢 Angular
Clues:
- angular.json
- src/app/
- *.component.ts

📌 Meaning:
👉 Enterprise frontend framework

## 🟢 Vue.js
Clues:
- *.vue files
- vue.config.js
- src/components

📌 Meaning:
👉 Lightweight frontend UI

## 🔴 .NET Core (C# Backend)
Clues:
- .csproj
- Program.cs
- Controllers/

📌 Meaning:
👉 Enterprise backend API

## 🟤 Python Flask
Clues:
- app.py
- requirements.txt
- flask imports

📌 Meaning:
👉 Lightweight backend API

## ⚫ Django (Python Full Framework)
Clues:
- manage.py
- settings.py
- urls.py

📌 Meaning:
👉 Full backend + admin panel

## 🟡 Java Spring Boot
Clues:
- pom.xml
- src/main/java
- application.properties

📌 Meaning:
👉 Enterprise backend system

## 🔷 Mobile Apps

React Native:
- App.js
- android/
- ios/

Flutter:
- pubspec.yaml
- lib/main.dart

## 🟪 Static Website
Clues:
- index.html
- style.css
- script.js

📌 Meaning:
👉 Simple website (no framework)

# 🧱 DevOps Decision Formula
Always ask:
1. What language is it?
2. How does it run locally?
3. What output is generated?
4. How will it be served in production?

# 🚀 Docker Thinking Model
Step 1 → Choose Base Image  
Step 2 → Copy Code  
Step 3 → Install Dependencies  
Step 4 → Build Project  
Step 5 → Run Server
