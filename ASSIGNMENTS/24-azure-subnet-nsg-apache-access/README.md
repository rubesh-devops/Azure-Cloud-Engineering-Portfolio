# 🔐 Azure Networking – Subnet-Level NSG & Apache Web Server Access

---

## 📌 **Project Overview**

Configured **network security at the subnet level** by applying a **Network Security Group (NSG)** to the subnet hosting a **Linux (Ubuntu) virtual machine**, and validated web access by installing and exposing the **Apache2 web server**.

This assignment demonstrates how **Azure NSGs can be applied at both subnet and VM levels** to control traffic flow and securely expose applications.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Virtual Machine (Linux – Ubuntu)**
- **Azure Virtual Network**
- **Subnet**
- **Network Security Group (NSG)**
- **Apache2 Web Server**
- **HTTP (Port 80)**

---

## 🎯 **Objective**

To implement secure web access by:

- Reusing an existing Linux VM
- Installing Apache2 web server
- Applying an NSG at the **subnet level**
- Allowing HTTP traffic at both subnet and VM scope
- Verifying application accessibility via browser

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Linux VM Preparation**

- Used the **previously created Ubuntu VM**
- Connected via SSH
- Verified VM readiness for application installation

---

### 2️⃣ **Apache2 Installation**

- Installed **Apache2 web server**
- Started and enabled the Apache service
- Verified service status on the VM

---

### 3️⃣ **Subnet-Level NSG Configuration**

- Created a new **Network Security Group (NSG)**
- Associated the NSG with the **subnet** where the VM is deployed
- Added inbound rule to allow:
  - **HTTP (Port 80)**

---

### 4️⃣ **VM-Level NSG Rule Validation**

- Ensured NSG rules at the VM / NIC level allow **Port 80**
- Avoided rule conflicts between subnet and NIC
- Verified effective security rules

---

### 5️⃣ **Web Access Verification**

- Accessed the VM using its **public IP address**
- Confirmed successful loading of the **Apache2 default web page**
- Validated end-to-end network and application configuration

---

## 🔐 **Security & Governance Configuration**

- Implemented layered security using **subnet-level NSG**
- Restricted traffic to required ports only
- Followed Azure best practices for network segmentation
- Ensured controlled exposure of web services

---

## 📈 **Key Learning Outcomes**

- Subnet-level NSG configuration
- Difference between subnet and NIC-level security
- Apache2 installation and management
- Secure web server exposure on Azure
- Network troubleshooting and validation
- Azure networking best practices

---

## 🏆 **Real-World Use Case**

Subnet-level NSGs are commonly used for:

- Securing application tiers
- Enforcing shared security rules
- Web server hosting
- Multi-VM subnet protection
- Enterprise network segmentation

---

## 📊 **Outcome**

Successfully installed **Apache2 on a Linux VM**, applied **subnet-level NSG rules**, and verified **secure HTTP access**, demonstrating effective network security and application deployment on Azure.

---

## 🛠 **Skills Demonstrated**

- Azure Network Security Groups (NSG)
- Subnet-Level Security Configuration
- Azure Virtual Machines
- Linux (Ubuntu) Administration
- Apache2 Web Server
- Azure Networking Fundamentals
- Cloud Infrastructure Security

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1M1iJKgCFInHVjK1qHnE6InX0fjYs1pWO/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Networking – DevOps Architect Master’s Program (Intellipaat)**
