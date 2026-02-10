# 📦 Azure Container Registry & App Service – Containerized Application Deployment

---

## 📌 **Project Overview**

Implemented a **containerized application deployment workflow on Azure** by creating an **Azure Container Registry (ACR)**, integrating it with **Docker running on an Azure VM**, and deploying the container image using **Azure App Service**.

This assignment demonstrates how Azure supports **end-to-end container lifecycle management**—from image creation and registry storage to managed application hosting.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Virtual Machine (Linux)**
- **Docker Engine**
- **Azure Container Registry (ACR)**
- **Container Image**
- **Azure App Service (Web App for Containers)**
- **Azure Resource Manager (ARM)**

---

## 🎯 **Objective**

To implement a complete container deployment pipeline that:

- Creates a private container registry in Azure
- Connects Docker on a VM to Azure Container Registry
- Pushes a container image to ACR
- Deploys the containerized application using Azure App Service
- Demonstrates managed, scalable application hosting

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Azure Container Registry Creation**

- Created an **Azure Container Registry (ACR)**
- Configured registry access and authentication
- Verified successful ACR provisioning

---

### 2️⃣ **Docker Integration with ACR**

- Connected **Docker running on Azure VM** to ACR
- Authenticated Docker with Azure Container Registry
- Verified registry connectivity from the VM

---

### 3️⃣ **Container Image Upload to ACR**

- Tagged the locally created Docker image
- Pushed the image to **Azure Container Registry**
- Verified image availability in ACR repositories

---

### 4️⃣ **Azure App Service Deployment**

- Created an **Azure App Service (Web App for Containers)**
- Configured App Service to pull the image from ACR
- Deployed the containerized application
- Verified application accessibility via App Service URL

---

## 🔐 **Security & Governance Configuration**

- Used Azure-managed authentication for ACR access
- Restricted registry access to authorized services
- Leveraged App Service managed deployment
- Followed Azure best practices for container security

---

## 📈 **Key Learning Outcomes**

- Azure Container Registry (ACR) usage
- Docker image tagging and pushing
- Private container registry management
- App Service for containerized applications
- End-to-end container deployment on Azure
- Cloud-native application hosting

---

## 🏆 **Real-World Use Case**

This architecture is commonly used for:

- Hosting containerized web applications
- CI/CD pipelines with private registries
- Microservices deployment
- Startup and enterprise container platforms
- Managed application hosting without VM overhead

---

## 📊 **Outcome**

Successfully deployed a **containerized application on Azure App Service** using an image stored in **Azure Container Registry**, validating a complete and production-ready container deployment workflow.

---

## 🛠 **Skills Demonstrated**

- Azure Container Registry (ACR)
- Docker Image Management
- Azure App Service (Containers)
- Containerized Application Deployment
- Cloud-Native Architecture
- Azure Resource Management

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1wtYygJZNd0Yw6MgslO3Wd9JGWapgf1Bj/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure App & Container Services – DevOps Architect Master’s Program (Intellipaat)**
