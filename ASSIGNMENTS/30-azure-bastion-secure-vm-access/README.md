# 🔐 Azure Bastion – Secure Access to Private Virtual Machine

---

## 📌 **Project Overview**

Implemented **secure remote access to an Azure Virtual Machine without a public IP address** using **Azure Bastion**.

This assignment demonstrates how Azure Bastion enables **browser-based SSH/RDP connectivity** to private VMs, eliminating the need for public IP exposure and improving overall security posture.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Virtual Machine (Private)**
- **Azure Bastion Host**
- **Azure Virtual Network**
- **Subnet (AzureBastionSubnet)**
- **Network Security Group (NSG)**

---

## 🎯 **Objective**

To implement a secure access model that:

- Deploys a virtual machine **without a public IP**
- Uses **Azure Bastion** for remote connectivity
- Eliminates direct internet exposure
- Ensures secure administrative access

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Private VM Deployment**

- Created an **Azure Virtual Machine**
- Did **not assign a public IP address**
- Deployed VM within a secure virtual network
- Verified VM availability within the VNet

---

### 2️⃣ **Azure Bastion Setup**

- Created an **Azure Bastion Host**
- Configured the required **AzureBastionSubnet**
- Associated Bastion with the same virtual network
- Verified Bastion deployment success

---

### 3️⃣ **Secure VM Connection via Bastion**

- Used Azure Portal’s **Connect → Bastion** option
- Connected to the private VM using:
  - SSH (Linux) or RDP (Windows)
- Verified successful browser-based connection
- Confirmed VM access without public IP exposure

---

## 🔐 **Security & Governance Configuration**

- Removed public IP exposure completely
- Used Bastion for encrypted access
- Controlled access via NSG rules
- Followed Azure best practices for zero-trust networking

---

## 📈 **Key Learning Outcomes**

- Azure Bastion configuration
- Secure VM access without public IP
- Zero-trust networking principles
- Private VM administration
- Azure networking security best practices

---

## 🏆 **Real-World Use Case**

Azure Bastion is widely used for:

- Secure administrative access
- Production environment management
- Compliance-driven workloads
- Zero-trust architectures
- Enterprise cloud security models

---

## 📊 **Outcome**

Successfully deployed a **private Azure Virtual Machine** and accessed it securely using **Azure Bastion**, validating a **secure, production-ready access model** without public IP exposure.

---

## 🛠 **Skills Demonstrated**

- Azure Bastion
- Secure VM Access
- Private Networking
- Azure Virtual Machines
- Network Security Groups (NSG)
- Cloud Security Architecture

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1VXcwlrOKp7ejxqREGGNA8Xwr_Hjh2EUK/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Networking – DevOps Architect Master’s Program (Intellipaat)**
