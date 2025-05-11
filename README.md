# 🚀 OpenMetadata Deployment on Azure (Connected to AWS RDS)

This project sets up **OpenMetadata** on an Azure VM using **Docker** and connects it to an **AWS RDS MySQL** instance for metadata storage. Ideal for governance and metadata management use cases.

---

## 📦 What’s Included

- `docker-compose.yml` to run OpenMetadata in a Docker container.
- `.env` file template for secure configuration of your MySQL database.
- `cloud-init.yml` script to automate VM setup on Azure (optional).
- Simple instructions to deploy and access the metadata UI.

---

## 🛠️ Prerequisites

### ✅ Cloud Resources
- **Azure VM** (Ubuntu, Docker-compatible)
- **AWS RDS (MySQL)** database
  - Public access enabled
  - Port `3306` open to Azure VM IP

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/ask22me/openmeta-data.git
cd openmeta-data
