# 🚀 Continuous Deployment (CD) Project — Docker, GitHub & Docker Hub Integration

## 🐳 Dockerized Continuous Deployment App

### 📘 Project Overview
This project demonstrates a simple Flask web application containerized using Docker as part of a Continuous Deployment (CD) workflow.

It showcases how to:
- 🏗️ Build and run a lightweight Python Flask app  
- 🐋 Containerize it using Docker  
- ☁️ Push it to Docker Hub for easy deployment and sharing  
- 🔄 Maintain version control on GitHub for CI/CD integration  

---

## 🧩 Features
✅ Lightweight Python Flask web application  
✅ Fully Dockerized for platform-independent deployment  
✅ Integrated with GitHub & Docker Hub for CI/CD  
✅ Ideal for DevOps, Cloud, and Automation practice  

---

## ⚙️ Setup & Run Locally

### 1️⃣ Clone Repository
bash
git clone https://github.com/sunkandekar/flaskapp.git
cd flaskapp
2️⃣ Build Docker Image
bash
Copy code
docker build -t sunny-cd-app .
3️⃣ Run the Container
bash
Copy code
docker run -d -p 5000:5000 sunny-cd-app
Now open your browser and visit: 👉 http://localhost:5000

You should see:

csharp
Copy code
🚀 Hello from Sunny’s Dockerized CD App!
🐋 DockerHub Image
The prebuilt image is available publicly on Docker Hub. Pull it directly:

bash
Copy code
docker pull sunnykandekar/flaskapp:latest
🔗 Docker Hub Repository:
👉 https://hub.docker.com/r/sunnykandekar/flaskapp

🔗 All My Docker Repositories:
👉 https://hub.docker.com/u/sunnykandekar

📦 GitHub Repository
Full source code and Docker configuration are available here:
👉 https://github.com/sunkandekar/flaskapp

🧠 Step-by-Step CI/CD Guide (for Practice or Exam)
🧭 1. Initialize Git Repository
bash
Copy code
git init
git add .
git commit -m "Initial commit - Docker CD project"
🧭 2. Push Code to GitHub
bash
Copy code
git branch -M main
git remote add origin https://github.com/sunkandekar/flaskapp.git
git push -u origin main
✅ GitHub Repo: https://github.com/sunkandekar/flaskapp

🧭 3. Push Docker Image to Docker Hub
bash
Copy code
docker login
docker tag sunny-cd-app sunnykandekar/flaskapp:latest
docker push sunnykandekar/flaskapp:latest
✅ Docker Hub Repo: https://hub.docker.com/r/sunnykandekar/flaskapp

⚙️ Technologies Used
🐍 Python 3

🌶️ Flask

🐳 Docker

🌐 GitHub

☁️ Docker Hub

💡 Verification
You can view your image live at:
👉 https://hub.docker.com/r/sunnykandekar/flaskapp

Pull it and run locally:

bash
Copy code
docker pull sunnykandekar/flaskapp
docker run -p 5000:5000 sunnykandekar/flaskapp
🌟 About the Author
Sunny Kandekar —
🚀 Aspiring Cloud & DevOps Engineer passionate about containerization, automation, and scalable deployment workflows.

🐙 GitHub: https://github.com/sunkandekar

🐋 Docker Hub: https://hub.docker.com/u/sunnykandekar

Maintained by Sunny Kandekar | © 2025

yaml
Copy code

---

## ✅ How to Use This

### 🔹 For GitHub:
1. Create a file `README.md` in your `D:\flaskapp` folder.  
2. Paste the above content.  
3. Commit and push:
   bash
   git add README.md
   git commit -m "Added detailed project README"
   git push
   
🔹 For Docker Hub:
Go to https://hub.docker.com/r/sunnykandekar/flaskapp
Click Manage Repository → Edit Description
Paste the same markdown into the Overview box
Click Save
