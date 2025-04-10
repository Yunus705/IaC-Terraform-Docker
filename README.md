# 🐳 Terraform + Docker: Infrastructure as Code

This project demonstrates how to use **Terraform** to provision a **Docker container** using the Docker provider on a local machine (Docker Desktop).

---

## 📌 Task Objective

Provision a local **Docker container** using **Terraform**, perform operations like:
- `terraform init`
- `terraform plan`
- `terraform apply`
- `terraform destroy`
- Verify container creation using `docker ps`

---

## 🔧 Technologies Used

- Terraform
- Docker 
- Local machine (Windows)

---

## 📁 Project Structure

.
├── main.tf
├── README.md   <-- explain task steps
├── screenshots/
|   ├── init.png 
│   ├── plan_1.png
|   ├── plan_2.png
│   ├── apply.png
│   ├── docker_ps.png
│   ├── destroy_1.png
|   └── destroy_2.png

---

## How to Run

Clone this Repository

git clone https://github.com/Yunus705/IaC-Terraform-Docker.git

cd IaC-Terraform-Docker

1️⃣ Initialize Terraform

terraform init

2️⃣ Preview Plan

terraform plan

3️⃣ Apply Configuration

terraform apply -auto-approve

4️⃣ Verify Container

docker ps

🔍 Verifying the Setup

Once applied, Terraform will start an NGINX container accessible at:

📍 http://localhost:8080

Open it in your browser. You should see the NGINX welcome page.

5️⃣ Destroy Infrastructure

terraform destroy -auto-approve

---

🙋 Author

Yunus Sharif

📧 yunussharif705@gmail.com

📌 Note

Docker must be installed and running.

Tested on Terraform v1.5+ and Docker Desktop on Windows.