# DepiProject – Expense Tracker Application

## 📌 Overview

**DepiProject** is a full-stack web application that helps users track their expenses.  
It is built with **Python** for the backend logic and connected to a **NoSQL database** for storing expense records. The entire environment, including the database, is **containerized using Docker** and deployed on **AWS** using **Terraform** as the infrastructure-as-code solution.

---

## 🛠️ Technologies & Tools

| Technology | Purpose |
|------------|---------|
| Python     | Backend application logic |
| NoSQL DB   | Expense data storage |
| Docker     | Containerization of services |
| Terraform  | AWS infrastructure provisioning |
| AWS        | Cloud hosting and deployment |

---

## 📁 Project Structure

DepiProject/
├── main.tf # Terraform configuration
├── README.md # This file
├── requirements.txt # Python dependencies
├── app/ # Python application code
│ ├── ...
├── docker-compose.yml # Docker setup
└── .gitignore # Ignored files


---

## 🧠 Features

- Add, edit, and delete expense entries
- Connects to a NoSQL database (Docker container)
- Infrastructure deployed using Terraform
- Hosted on AWS cloud services

---

## 🚀 Prerequisites

Before starting, make sure you have:

- Git
- Docker & Docker Compose
- Python 3.x
- Terraform (v1.0+)
- An AWS account configured with credentials

---

## 📌 Setup & Deployment

### 
1️⃣ **Clone the Repository**
```bash
git clone https://github.com/OmarEzzat96/DepiProject.git
cd DepiProject
2️⃣ Start Docker Containers

This will launch the database and any other required services:

docker-compose up -d

3️⃣ Install Python Dependencies
pip install -r requirements.txt

4️⃣ Terraform Initialization
terraform init

5️⃣ Review Infrastructure Plan
terraform plan

6️⃣ Apply Infrastructure

Deploy the stack to AWS:

terraform apply

🧹 Destroy Infrastructure

To tear down and remove all deployed resources:

terraform destroy

📦 What’s Inside

Python application with routes and logic for managing expenses

Docker setup for database

Terraform scripts for provisioning AWS resources

📈 Future Enhancements

Add user authentication

Create frontend UI with React or Vue.js

Add monitoring and alerting for cloud infrastructure
