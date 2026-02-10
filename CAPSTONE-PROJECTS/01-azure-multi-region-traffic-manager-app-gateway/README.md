# 🌐 Azure Multi-Region Web Application with Traffic Manager & Application Gateway

---

## 📌 Project Overview

This capstone project showcases the design and implementation of a **highly available, multi-region web application architecture on Microsoft Azure**.  
The solution leverages **Azure Traffic Manager** for global traffic distribution and **Azure Application Gateway** for intelligent request routing within each region.

The application is deployed across **Central US** and **West US** regions to ensure **high availability, fault tolerance, and optimal performance**, while also supporting **custom error handling** and **secure file uploads** using Azure-native services.

---

## 🏗 Architecture Components

- 🌍 **Azure Traffic Manager** – Global DNS-based traffic routing  
- 🚦 **Azure Application Gateway** – Path-based request routing and error handling  
- 🌐 **Azure Virtual Networks (VNet–VNet Peering)** – Secure inter-region connectivity  
- 🖥 **Azure Virtual Machines (Ubuntu Linux)** – Backend application hosting  
- 💾 **Azure Blob Storage**
  - Static Website (Custom Error Pages)
  - Blob Container (File Uploads)
- 🌐 **Azure DNS** – Domain resolution
- 🧠 **Python-based Web Application**

---

## 🧭 Architecture Flow

- Incoming user requests are first handled by **Azure Traffic Manager**
- Traffic Manager routes users to the optimal Azure region
- Each region uses **Azure Application Gateway** as the single entry point
- Application Gateway applies **path-based routing logic**
- Backend virtual machines serve application content:
  - 🏠 **Home Page** served from VM2
  - 📤 **Upload Page** served from VM1
- 🚫 **Custom error pages (403 & 502)** are served from Azure Blob Static Website
- 🔗 Virtual networks across regions communicate securely using **VNet–VNet Peering**

---

## 🎯 Functional Requirements Implemented

### 🖥 Web Pages
- 🏠 Home Page (Default) → VM2  
- 📤 Upload Page (`/upload`) → VM1  
- 🚫 Error Pages (403 & 502) → Azure Blob Static Website  

### 🚦 Routing Logic
- Root domain routes to the Home Page
- `/upload` path routes to the Upload Page
- Application Gateway redirects error responses to `error.html`

> ℹ️ **Note**  
> The domain name (`example.com`) represents the **Azure Traffic Manager DNS endpoint**.

---

## ⚙️ Implementation Overview

### 🌍 Multi-Region Deployment
- Resources deployed independently in **Central US** and **West US**
- Dedicated Virtual Networks created per region
- Secure inter-region communication enabled via **VNet–VNet Peering**

---

### 🖥 Compute Layer
- Linux virtual machines hosted within private networks
- Separate VMs used for different application roles
- Backend services isolated from direct public access

---

### 💾 Storage Layer
- Azure Storage Account configured for:
  - Static Website hosting (custom error pages)
  - Blob container for file uploads
- Application configured to interact securely with Azure Storage

---

### 🚦 Traffic & Load Management
- Azure Application Gateway manages inbound traffic
- Path-based routing ensures correct backend selection
- Azure Traffic Manager distributes traffic globally based on performance

---

## 🔐 Security & Networking Design

- 🔒 Backend virtual machines hosted in private VNets
- 🚫 No direct public IP exposure for backend VMs
- 🚦 Application Gateway acts as the controlled ingress point
- 🛡 Network Security Groups restrict traffic to required ports only
- 🌐 Centralized routing and security enforcement

---

## 📈 Key Learning Outcomes

- Designing multi-region Azure architectures
- Implementing DNS-based global traffic routing
- Applying path-based routing with Application Gateway
- Hosting static content using Azure Blob Storage
- Integrating secure file upload workflows
- Establishing VNet–VNet peering
- Understanding enterprise-grade availability and resiliency concepts

---

## 🏆 Real-World Use Case

This architecture pattern is commonly used for:
- 🌍 Global web applications
- 🏢 Enterprise SaaS platforms
- 🚀 Highly available production workloads
- 🔄 Regional disaster recovery strategies
- 🔐 Secure upload portals
- ☁️ Cloud-native frontend architectures

---

## 📊 Outcome

Successfully delivered a **fault-tolerant, multi-region Azure web application** with:
- Intelligent path-based routing
- Custom error handling
- Secure file upload capability
- Optimized global traffic distribution
- High availability across regions

---

## 🛠 Skills Demonstrated

- Azure Traffic Manager  
- Azure Application Gateway  
- Azure Virtual Networks & Peering  
- Azure Blob Storage (Static Website)  
- Linux Virtual Machines  
- Cloud Networking & Security  
- High Availability Architecture  
- Azure DNS  

---

## 📸 Proof of Implementation

📄 **Consolidated Capstone Execution PDf**  
(https://drive.google.com/file/d/1XEnVs2hR6xMZkFtZwREwPVGjt5I5KS3G/view?usp=drive_link)

---

## 📚 Course Reference

Capstone Project completed as part of:

**DevOps Architect Master’s Program – Intellipaat**
