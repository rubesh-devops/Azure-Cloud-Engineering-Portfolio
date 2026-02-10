# 📌 Azure Virtual Machine – Static Public IP Assignment

---

## 📌 **Project Overview**

Implemented **static public IP addressing for an Azure Virtual Machine** to ensure a **persistent and predictable network endpoint**.

This assignment demonstrates how Azure networking allows VMs to retain a fixed public IP address, which is essential for applications requiring consistent external access, DNS mapping, and firewall whitelisting.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Virtual Machine**
- **Azure Public IP Address (Static)**
- **Azure Virtual Network**
- **Network Security Group (NSG)**

---

## 🎯 **Objective**

To configure a networking setup that:

- Deploys a virtual machine in **West US**
- Assigns a **Static Public IP address** to the VM
- Ensures consistent external connectivity
- Supports production-grade network configurations

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Virtual Machine Deployment**

- Created an **Azure Virtual Machine**
- Selected:
  - **Region:** West US
- Verified successful VM provisioning
- Ensured VM was attached to a virtual network

---

### 2️⃣ **Static Public IP Configuration**

- Created a **Public IP Address resource**
- Set allocation method to **Static**
- Associated the static IP with the VM’s network interface
- Verified IP persistence across VM restarts

---

## 🔐 **Security & Governance Configuration**

- Controlled inbound traffic using **Network Security Group (NSG)**
- Restricted exposed ports to required services only
- Ensured predictable IP-based access control
- Followed Azure best practices for public-facing workloads

---

## 📈 **Key Learning Outcomes**

- Azure Public IP management
- Static vs Dynamic IP addressing
- VM network interface configuration
- NSG-based access control
- Azure networking fundamentals
- Production-ready VM networking

---

## 🏆 **Real-World Use Case**

Static public IPs are commonly used for:

- Public-facing web servers
- API endpoints
- Firewall and IP whitelisting
- DNS mapping
- External service integrations

---

## 📊 **Outcome**

Successfully deployed an **Azure Virtual Machine in West US** with a **static public IP address**, ensuring reliable and consistent external connectivity.

---

## 🛠 **Skills Demonstrated**

- Azure Virtual Machines
- Azure Public IP (Static)
- Azure Networking
- Network Security Groups (NSG)
- Cloud Infrastructure Configuration
- Azure Resource Management

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/12IV2af6K_J9TDs1Y09x5hJLWpvhul5FX/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Networking – DevOps Architect Master’s Program (Intellipaat)**
