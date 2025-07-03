# 🚀 Dockerized Node.js Website

This is a simple, responsive, and modern Node.js application that serves a fully styled HTML webpage with interactive buttons — all containerized using Docker.
---
## 🧱 Project Structure
docker-node-app/
├── app.js # Node.js HTTP server (no frameworks)
├── Dockerfile # Dockerfile to build the image
├── package.json # Node.js project metadata
└── public/
└── index.html # Frontend: HTML + CSS + Buttons

---
## 🌐 Features

- 🔹 Node.js HTTP server (no Express.js)
- 🔹 Modern HTML + CSS UI
- 🔹 Interactive buttons (`alert`, `reload`)
- 🔹 Fully Dockerized
- 🔹 Local preview at `http://localhost:4000`
---
## 🚀 Run Locally Using Docker

### Step 1: Clone the Repository

```bash
git clone https://github.com/Chilukaganesh5/docker-node-app.git
cd docker-node-app

Step 2: Build Docker Image
docker build -t my-node-app .

Step 3: Run the Container
docker run -p 4000:3000 my-node-app

Now open your browser at:
http://localhost:4000

![image](https://github.com/user-attachments/assets/1435fa5e-a19e-4235-a1d1-bf32d16a0dff)

🔄 Future Improvements
Use Express.js for routing

Add multiple HTML pages

Externalize CSS and JavaScript

Add Docker Compose support

Deploy to AWS, Render, or Railway

🧑‍💻 Author
Chiluka Ganesh
💼 GitHub
🔗 LinkedIn

🏷️ Tags
#Docker #NodeJS #DevOps #100DaysOfDevOps #WebApp #Containers

