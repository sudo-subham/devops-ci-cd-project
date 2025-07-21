# 📦 DevOps CI/CD Project

This project demonstrates a complete CI/CD pipeline using **Jenkins**, **Docker**, and **AWS EC2** for deploying a basic static HTML web application.

---

## 🔧 Tech Stack & Tools Used

| Tool            | Purpose                                |
|------------------|----------------------------------------|
| Git + GitHub     | Version control and source code hosting |
| Jenkins          | Continuous Integration & Deployment    |
| Docker           | Containerization of the application    |
| Docker Hub       | Hosting Docker images                  |
| AWS EC2          | Running the Dockerized application     |
| AWS IAM          | Secure access control for services     |
| CloudWatch       | Monitoring logs & basic metrics        |

---

## 📁 Project Structure

devops-ci-cd-project/
├── index.html # Simple HTML homepage
├── style.css # Basic CSS styling
└── Dockerfile # Nginx-based Docker image config

---

## 🚀 CI/CD Pipeline Flow

1. Developer pushes code to GitHub
2. Jenkins (CI) is triggered on push
3. Jenkins builds Docker image using `Dockerfile`
4. Jenkins tags and pushes the image to Docker Hub
5. Jenkins (CD) pulls the image from Docker Hub
6. Jenkins deploys the container on AWS EC2 (port 80)
7. AWS CloudWatch monitors logs & container metrics

---

## ✅ Project Goal

> **Automate the deployment of a static web application** using modern DevOps practices, making it faster, scalable, and production-ready.

---

## 🌐 Live Demo

App hosted at:
http://51.21.170.143

## 👨‍💻 Author

**Name:** Shubham Pathak  
**Role:** DevOps Trainee  
**Internship:** Cloud Counselage Global – Professional Internship  
**GitHub:** [https://github.com/sudo-subham](https://github.com/sudo-subham)

