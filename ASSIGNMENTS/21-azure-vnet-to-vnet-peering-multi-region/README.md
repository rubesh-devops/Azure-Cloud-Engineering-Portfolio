# 🌐 Azure Virtual Network Peering – Multi-Region Private Connectivity

---

## 📌 **Project Overview**

Designed and implemented **private network connectivity between two Azure Virtual Networks (VNets)** deployed in **different regions** using **VNet-to-VNet peering**.

This assignment demonstrates how Azure enables **secure, low-latency, private communication** across regions without using the public internet—an essential concept for enterprise and multi-region architectures.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Virtual Network (West US)**
- **Azure Virtual Network (South India)**
- **Azure Virtual Machines**
- **VNet-to-VNet Peering**
- **Network Security Groups (NSG)**
- **Private IP Connectivity**

---

## 🎯 **Objective**

To build a multi-region Azure networking setup that:

- Creates isolated VNets in different regions
- Deploys VMs within their respective VNets
- Establishes **VNet-to-VNet peering**
- Enables **private communication** between VMs
- Validates connectivity using private IP addresses

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Virtual Network Creation**

- Created an **Azure Virtual Network** in:
  - **Region:** West US
- Created another **Azure Virtual Network** in:
  - **Region:** South India
- Configured address spaces to avoid overlap

---

### 2️⃣ **Virtual Machine Deployment**

- Deployed a **Virtual Machine** in:
  - West US VNet
- Deployed another **Virtual Machine** in:
  - South India VNet
- Verified successful VM provisioning and network attachment

---

### 3️⃣ **VNet-to-VNet Peering Configuration**

- Configured **VNet peering** between:
  - West US VNet ↔ South India VNet
- Enabled:
  - Allow virtual network access
- Verified peering status on both VNets

---

### 4️⃣ **Private Connectivity Validation**

- Logged into **VM1**
- Used the **ping command** to reach **VM2** using its **private IP address**
- Verified successful ICMP response
- Confirmed private, cross-region communication

---

## 🔐 **Security & Governance Configuration**

- Used private IP communication only
- Controlled traffic using **Network Security Groups**
- Avoided public internet exposure
- Followed Azure best practices for secure networking

---

## 📈 **Key Learning Outcomes**

- Azure Virtual Network design
- Multi-region networking concepts
- VNet-to-VNet peering configuration
- Private IP-based communication
- NSG-based traffic control
- Azure networking troubleshooting

---

## 🏆 **Real-World Use Case**

VNet peering is commonly used for:

- Multi-region application architectures
- Disaster recovery setups
- Hybrid cloud networking
- Microservices communication across regions
- Secure enterprise network design

---

## 📊 **Outcome**

Successfully established **private network connectivity between two Azure VMs deployed in different regions**, validating **secure, low-latency communication via VNet peering**.

---

## 🛠 **Skills Demonstrated**

- Azure Virtual Networks (VNet)
- VNet-to-VNet Peering
- Azure Virtual Machines
- Private IP Networking
- Network Security Groups (NSG)
- Multi-Region Cloud Architecture
- Azure Networking Fundamentals

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1CcV_KJpGweJU6WQ9dM0SASbtRNuu7XNu/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Networking – DevOps Architect Master’s Program (Intellipaat)**
