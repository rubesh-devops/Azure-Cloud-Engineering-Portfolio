# 📈 Azure Virtual Machine Scale Sets – Auto Scaling with CPU Metrics

---

## 📌 **Project Overview**

Designed and implemented an **auto-scaling compute solution using Azure Virtual Machine Scale Sets (VMSS)** with **Ubuntu Linux** as the operating system.

This assignment demonstrates how Azure enables **horizontal scaling** of virtual machines based on **CPU utilization**, ensuring performance, availability, and cost efficiency for variable workloads.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Virtual Machine Scale Set (VMSS)**
- **Ubuntu Linux Image**
- **Azure Virtual Network**
- **Network Security Group (NSG)**
- **Azure Monitor (CPU Metrics)**
- **Auto Scaling Rules**

---

## 🎯 **Objective**

To implement an automated scaling solution that:

- Deploys a VM Scale Set using Ubuntu OS
- Maintains a minimum and maximum VM count
- Scales out based on high CPU utilization
- Scales in based on low CPU utilization
- Ensures application availability and cost optimization

---

## ⚙️ **Implementation Steps**

### 1️⃣ **VM Scale Set Creation**

- Created an **Azure Virtual Machine Scale Set**
- Selected:
  - **Operating System:** Ubuntu Linux
- Configured instance limits:
  - **Minimum instances:** 1
  - **Maximum instances:** 5
- Verified successful VMSS deployment

---

### 2️⃣ **Scale-Out Configuration**

- Configured **scale-out rule** based on CPU metrics
- Trigger condition:
  - **CPU utilization ≥ 75%**
- Action:
  - **Increase instance count by 1 VM**
- Ensured scaling responds to increased load

---

### 3️⃣ **Scale-In Configuration**

- Configured **scale-in rule** based on CPU metrics
- Trigger condition:
  - **CPU utilization ≤ 25%**
- Action:
  - **Decrease instance count by 1 VM**
- Ensured cost optimization during low usage

---

## 🔐 **Security & Governance Configuration**

- Applied NSG rules for controlled network access
- Used Azure-managed identity and monitoring
- Followed Azure best practices for scalable compute
- Ensured automated scaling without manual intervention

---

## 📈 **Key Learning Outcomes**

- Azure VM Scale Set deployment
- Auto scaling configuration using CPU metrics
- Linux VM scalability on Azure
- Azure Monitor integration
- High availability design
- Cost-efficient cloud infrastructure management

---

## 🏆 **Real-World Use Case**

VM Scale Sets are commonly used for:

- Web and application servers
- Microservices-based workloads
- Traffic-driven applications
- Backend processing systems
- Elastic compute environments
- Production workloads requiring high availability

---

## 📊 **Outcome**

Successfully deployed an **Ubuntu-based VM Scale Set** with **dynamic auto scaling**, allowing the environment to automatically scale out during high CPU usage and scale in during low demand.

---

## 🛠 **Skills Demonstrated**

- Azure Virtual Machine Scale Sets (VMSS)
- Auto Scaling Configuration
- Azure Monitor & Metrics
- Linux (Ubuntu) Administration
- Cloud Compute Scalability
- High Availability Architecture
- Cost Optimization Strategies

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1ZFrMf0Z5nZcFm_zSNMTz5r9scPhhYHfN/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Cloud Training – DevOps Architect Master’s Program (Intellipaat)**
