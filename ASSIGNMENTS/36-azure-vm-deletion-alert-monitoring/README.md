# 🚨 Azure Monitoring – Alert for Virtual Machine Deletion

---

## 📌 **Project Overview**

Implemented a **monitoring and alerting mechanism** in Azure to detect and notify when a **Virtual Machine deletion event** occurs.

This assignment demonstrates how **Azure Monitor and Log Analytics** can be used to track **critical resource-level events** and trigger alerts for security, governance, and operational awareness.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Virtual Machine**
- **Azure Monitor**
- **Azure Log Analytics Workspace**
- **Activity Log Alerts**
- **Alert Rules & Action Groups**

---

## 🎯 **Objective**

To ensure operational and security awareness by:

- Monitoring deletion events of Azure Virtual Machines
- Creating an alert rule for VM deletion
- Triggering notifications when a delete action occurs
- Preventing unnoticed or accidental resource removal

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Reuse Existing Virtual Machine**

- Used the **previously deployed Azure Virtual Machine**
- Verified VM presence and activity logging
- Ensured VM was connected to monitoring services

---

### 2️⃣ **Azure Monitor Alert Configuration**

- Created an **Azure Monitor alert rule**
- Selected **Activity Log** as the signal source
- Configured condition to detect:
  - **Delete Virtual Machine** operation
- Scoped the alert to the VM / resource group

---

### 3️⃣ **Action Group Setup**

- Created or selected an **Action Group**
- Configured notification method:
  - Email / SMS / Azure App (as applicable)
- Linked Action Group to the alert rule

---

### 4️⃣ **Alert Validation**

- Simulated / validated the delete operation
- Verified alert triggering
- Confirmed notification delivery
- Ensured alert accuracy and reliability

---

## 🔐 **Security & Governance Configuration**

- Monitored critical destructive actions
- Enabled audit-level visibility
- Supported compliance and governance requirements
- Followed Azure best practices for monitoring and alerting

---

## 📈 **Key Learning Outcomes**

- Azure Activity Log monitoring
- Alert rule creation
- Event-based alerting
- Action Groups and notifications
- Cloud governance and security monitoring
- Proactive incident detection

---

## 🏆 **Real-World Use Case**

Deletion alerts are commonly used for:

- Preventing accidental resource deletion
- Security incident detection
- Compliance auditing
- Production environment protection
- Enterprise cloud governance

---

## 📊 **Outcome**

Successfully configured an **Azure Monitor alert** to detect and notify on **Virtual Machine deletion events**, ensuring proactive monitoring and improved security posture.

---

## 🛠 **Skills Demonstrated**

- Azure Monitor
- Activity Log Alerts
- Azure Log Analytics
- Alert Rules & Action Groups
- Cloud Security Monitoring
- Azure Governance & Compliance

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1GGbmAF7XWbmv39WIcG4zNwupEVO9iEDN/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Monitoring – DevOps Architect Master’s Program (Intellipaat)**
