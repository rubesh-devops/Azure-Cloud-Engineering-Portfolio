# 🚦 Azure Application Gateway – Path-Based Routing to Multiple Web VMs

---

## 📌 **Project Overview**

Implemented **path-based routing using Azure Application Gateway** to route incoming web traffic to **different backend virtual machines** based on URL paths.

This assignment demonstrates how **Azure Application Gateway (Layer 7 load balancer)** enables intelligent traffic routing, making it ideal for modern web and microservices architectures.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Application Gateway**
- **Azure Virtual Machines (Ubuntu – VM1 & VM2)**
- **Apache2 Web Server**
- **Azure Virtual Network**
- **Backend Pools**
- **HTTP Listeners**
- **Routing Rules**

---

## 🎯 **Objective**

To configure a Layer-7 routing solution that:

- Uses **Azure Application Gateway**
- Routes traffic based on URL paths
- Sends `/vm1` requests to **VM1**
- Sends `/vm2` requests to **VM2**
- Demonstrates application-level traffic control

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Backend Web Server Preparation**

- Used **two Ubuntu VMs** with Apache2 installed
- Configured web content on:
  - **VM1** to respond to `/vm1`
  - **VM2** to respond to `/vm2`
- Verified backend VM accessibility

---

### 2️⃣ **Application Gateway Creation**

- Created an **Azure Application Gateway**
- Configured:
  - Frontend IP (Public)
  - HTTP listener
  - Backend pools for VM1 and VM2
- Verified successful gateway provisioning

---

### 3️⃣ **Path-Based Routing Configuration**

- Created **routing rules**:
  - `/vm1` → Backend Pool (VM1)
  - `/vm2` → Backend Pool (VM2)
- Linked routing rules to HTTP listener
- Enabled path-based routing functionality

---

### 4️⃣ **Traffic Validation**

- Accessed Application Gateway public IP:
  - `http://<gateway-ip>/vm1`
  - `http://<gateway-ip>/vm2`
- Verified correct routing to respective VMs
- Confirmed application-level traffic control

---

## 🔐 **Security & Governance Configuration**

- Allowed HTTP traffic using NSG rules
- Restricted backend access to Application Gateway
- Used Layer-7 inspection and routing
- Followed Azure best practices for web traffic management

---

## 📈 **Key Learning Outcomes**

- Azure Application Gateway configuration
- Layer-7 load balancing concepts
- Path-based routing implementation
- Backend pool management
- Web traffic routing strategies
- Azure networking (L7)

---

## 🏆 **Real-World Use Case**

Application Gateway is widely used for:

- Microservices routing
- Multi-application hosting
- URL-based traffic distribution
- Web Application Firewall (WAF) integration
- Enterprise-grade web architectures

---

## 📊 **Outcome**

Successfully configured **Azure Application Gateway** with **path-based routing**, directing `/vm1` and `/vm2` traffic to their respective backend virtual machines.

---

## 🛠 **Skills Demonstrated**

- Azure Application Gateway
- Path-Based Routing
- Layer-7 Load Balancing
- Apache2 Web Servers
- Azure Virtual Machines
- Advanced Azure Networking

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1x6dI9ck6LHlS4cpHZnlEih4hlLhfUcyP/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Networking – DevOps Architect Master’s Program (Intellipaat)**
