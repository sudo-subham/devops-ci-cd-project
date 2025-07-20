📦 DevOps CI/CD Project
This project demonstrates a complete CI/CD pipeline using Jenkins, Docker, and AWS EC2 for deploying a basic HTML web application.

🔧 Tech Stack & Tools Used
Git + GitHub – Version control

Jenkins – Continuous Integration & Delivery

Docker – Containerization of the app

Docker Hub – Hosting container images

AWS EC2 – Hosting and running the Dockerized app

AWS IAM – Secure access control

CloudWatch – Basic monitoring and logs

📁 Project Structure
bash
Copy
Edit
├── index.html        # Simple HTML homepage
├── style.css         # Basic styling
└── Dockerfile        
🚀 Pipeline Flow
Developer pushes code to GitHub

Jenkins pulls the latest code

Builds Docker image using Dockerfile

Pushes image to Docker Hub

Deploys container to AWS EC2 instance

CloudWatch monitors logs & metrics

✅ Goal
Automate the deployment process of a static web app to make it faster, reliable, and scalable using DevOps practices.

👨‍💻 Author
Shubham Pathak – DevOps Trainee (Cloud Counselage Internship)

