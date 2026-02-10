# 🌍 Azure Traffic Manager – Geographic Load Balancing Across Regions

---

## 📌 **Project Overview**

Implemented **geographic load balancing using Azure Traffic Manager** to distribute user traffic across **virtual machines deployed in different Azure regions**.

This assignment demonstrates how **Azure Traffic Manager (DNS-based load balancer)** improves **availability, performance, and resilience** by routing users to the nearest or healthiest endpoint.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Virtual Machines (Multi-Region)**
- **Azure Traffic Manager**
- **Public IP / DNS Endpoints**
- **Azure DNS**
- **Network Security Group (NSG)**

---

## 🎯 **Objective**

To design a globally distributed architecture that:

- Deploys virtual machines in **different Azure regions**
- Configures **Azure Traffic Manager**
- Distributes traffic geographically
- Improves application availability and user experience

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Multi-Region VM Deployment**

- Deployed **two Azure Virtual Machines** in:
  - Different Azure regions
- Installed and configured required services (e.g., Apache2)
- Verified individual VM accessibility

---

### 2️⃣ **Traffic Manager Profile Creation**

- Created an **Azure Traffic Manager profile**
- Selected **Routing Method**:
  - **Geographic** (or Performance-based as applicable)
- Configured profile settings and DNS name

---

### 3️⃣ **Endpoint Configuration**

- Added VM public IPs / DNS names as **endpoints**
- Assigned endpoints to respective geographic regions
- Configured health probes to monitor VM availability

---

### 4️⃣ **Traffic Routing Validation**

- Accessed the **Traffic Manager DNS name**
- Tested routing behavior from different locations
- Verified traffic distribution based on geography
- Confirmed high availability and failover behavior

---

## 🔐 **Security & Governance Configuration**

- Controlled inbound access using NSGs
- Exposed only required application ports
- Used Azure-managed DNS-based routing
- Followed best practices for global traffic management

---

## 📈 **Key Learning Outcomes**

- Azure Traffic Manager configuration
- DNS-based global load balancing
- Multi-region architecture design
- Geographic traffic routing
- High availability & disaster recovery concepts
- Cloud networking at global scale

---

## 🏆 **Real-World Use Case**

Azure Traffic Manager is commonly used for:

- Global web applications
- Disaster recovery setups
- Multi-region SaaS platforms
- Latency-based traffic routing
- High availability architectures

---

## 📊 **Outcome**

Successfully deployed **multi-region virtual machines** and configured **Azure Traffic Manager** to balance traffic geographically, ensuring improved performance, availability, and resilience.

---

## 🛠 **Skills Demonstrated**

- Azure Traffic Manager
- Multi-Region Deployment
- Geographic Load Balancing
- Azure DNS
- Cloud High Availability Architecture
- Advanced Azure Networking

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/10fwdr0ooaNSzHrk_6ZQ1ltwz3agDbOQb/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Networking – DevOps Architect Master’s Program (Intellipaat)**
