# DevOps  Project

This is a full-stack web application deployed on an AWS EC2 instance using Docker and Docker Compose.
It demonstrates containerization, reverse proxy configuration, and database connectivity.

## 🚀 Tech Stack
- **Frontend:** HTML, Nginx (Reverse Proxy)
- **Backend:** Node.js
- **Database:** PostgreSQL
- **Deployment:** AWS EC2 (Ubuntu), Docker, Docker Compose

## 🛠️ Deployment Steps

 **Clone the repository on your EC2 server:**
   ```bash
   git clone [https://github.com/vishaljadhav2302-sudo/devops-project.git](https://github.com/vishaljadhav2302-sudo/devops-project.git)
   cd devops-project

1:- Build and run the Docker containers:
  Bash
  sudo docker compose up -d --build

2:- Access the application:
Open a web browser and navigate to the EC2 Public IP address.

Note: The AWS EC2 instance has been terminated to avoid cloud billing. Please refer to the deployment screenshot below for the live working output of the project.
