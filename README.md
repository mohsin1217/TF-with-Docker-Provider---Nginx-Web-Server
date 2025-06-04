
# Terraform + Docker: Nginx Container (Local)

This project uses **Terraform** and the **Docker provider** to deploy an Nginx container on your local system.

## 🧰 Tech Stack

- Terraform (CLI)
- Docker Desktop
- Docker Provider for Terraform (`kreuzwerker/docker`)
- VS Code (for editing and terminal)

## 📁 Project Structure

```
terraform-docker-nginx/
├── main.tf         # Contains Docker provider and container config
├── outputs.tf      # Outputs container name
├── README.md       # Project documentation (this file)
```

## 🚀 How to Run

### Step 1: Prerequisites

Make sure you have:
- Docker installed and running (`docker ps` should work)
- Terraform installed (`terraform -version`)
- Internet access (to pull Docker image)

### Step 2: Initialize Terraform

```bash
terraform init
```

### Step 3: Apply the Configuration

```bash
terraform apply
```

Approve the prompt by typing `yes`.

### Step 4: Access the Nginx Web Server

Open your browser and go to:

```
http://localhost:8080
```

You’ll see the default Nginx welcome page.

### Step 5: Clean Up

```bash
terraform destroy
```

---

## 🧠 What You Learn

- Use Terraform to automate Docker container deployment
- Work with providers (`docker`)
- Manage infrastructure as code even without a cloud account

## 🙋‍♂️ Author

**Sayed Mohsin Ali**  
🔗 [GitHub](https://github.com/mohsin1217)  
🔗 [LinkedIn](https://www.linkedin.com/in/sayed-mohsin-ali-2a68a124a/)
