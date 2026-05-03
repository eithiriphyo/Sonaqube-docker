# 🚀 CI/CD Pipeline for Static Website Deployment

## 📌 Project Overview
This project demonstrates a complete CI/CD pipeline to automate the deployment of a static website using Jenkins, Docker, and AWS EC2.

The pipeline automatically builds and deploys a containerized web application whenever changes are pushed to GitHub.

## 🛠️ Tech Stack
- AWS EC2
- Jenkins (CI/CD)
- Docker
- Nginx
- Git & GitHub
- HTML, CSS, JavaScript

---

## ⚙️ Architecture
GitHub → Jenkins → Docker Build → Docker Container → Nginx Server → Live Website

---

## 🚀 Features
- Automated build using Jenkins
- Containerized web application using Docker
- Deployment on AWS EC2 instance
- Zero manual deployment effort
- Lightweight static website hosting

---

## 🐳 Docker Setup
```bash
docker build -t my-website .
docker run -d -p 8081:80 my-website
