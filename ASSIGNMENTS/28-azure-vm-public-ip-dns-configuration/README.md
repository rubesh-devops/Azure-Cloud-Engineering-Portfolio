# 🌐 Azure DNS – Public IP DNS Configuration for Virtual Machines

---

## 📌 **Project Overview**

Configured **DNS names for the public IP addresses** of two Azure Virtual Machines to enable **human-readable, DNS-based access** instead of raw IP addresses.

This assignment demonstrates how Azure supports **public DNS labeling for VM endpoints**, improving accessibility, manageability, and professional deployment practices.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Virtual Machines (VM1 & VM2)**
- **Azure Public IP Addresses**
- **Azure DNS (Public IP DNS Label)**
- **Azure Virtual Network**
- **Network Security Group (NSG)**

---

## 🎯 **Objective**

To enable DNS-based access by:

- Using the two previously deployed VMs
- Configuring DNS labels for each VM’s public IP
- Allowing access to VMs via DNS names instead of IPs
- Validating DNS resolution and connectivity

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Reuse Existing Virtual Machines**

- Used the **two previously created Azure VMs**
- Verified public IP assignment for each VM
- Ensured VMs were accessible via public IP

---

### 2️⃣ **Public IP DNS Label Configuration**

- Opened the **Public IP Address** resource for each VM
- Configured a **DNS name label** for:
  - **VM1 Public IP**
  - **VM2 Public IP**
- Saved configuration and verified DNS name generation

---

### 3️⃣ **DNS Resolution Validation**

- Accessed each VM using its **DNS name**
- Verified successful resolution to public IP
- Confirmed application / service accessibility via DNS

---

## 🔐 **Security & Governance Configuration**

- Controlled inbound traffic using NSGs
- Exposed only required ports (HTTP / SSH)
- Used Azure-managed DNS infrastructure
- Followed best practices for public endpoint exposure

---

## 📈 **Key Learning Outcomes**

- Azure Public IP DNS labeling
- DNS fundamentals in Azure
- VM accessibility using DNS names
- Public endpoint management
- Azure networking best practices

---

## 🏆 **Real-World Use Case**

DNS configuration for VM public IPs is commonly used for:

- Public-facing web servers
- Application endpoints
- Easier access management
- Development and testing environments
- Professional cloud deployments

---

## 📊 **Outcome**

Successfully configured **DNS names for the public IPs of two Azure Virtual Machines**, enabling reliable and user-friendly access using DNS instead of static IP addresses.

---

## 🛠 **Skills Demonstrated**

- Azure DNS
- Public IP Management
- DNS Name Label Configuration
- Azure Virtual Machines
- Network Security Groups (NSG)
- Cloud Networking Fundamentals

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1knfAgmxDU8MkHSpySDIHi0JqJ898iouR/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Networking – DevOps Architect Master’s Program (Intellipaat)**
