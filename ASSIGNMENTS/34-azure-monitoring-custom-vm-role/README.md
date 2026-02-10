# 📊 Azure Monitoring – Custom RBAC Role for VM Operational Access

---

## 📌 **Project Overview**

Implemented a **custom Azure RBAC role** focused on **operational monitoring and control of virtual machines**, allowing users to **view VM details and start/stop VMs**, while explicitly restricting all other actions.

This assignment highlights how **Azure Monitoring and RBAC work together** to provide controlled operational access without compromising security.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Role-Based Access Control (RBAC)**
- **Azure Virtual Machines**
- **Custom Role Definition**
- **Azure Active Directory (Entra ID)**

---

## 🎯 **Objective**

To create a monitoring-focused access model that:

- Allows visibility into VM resources
- Permits operational control (start / stop VMs)
- Restricts configuration, networking, and deletion actions
- Enforces least-privilege access for monitoring roles

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Custom RBAC Role Creation**

- Created a **custom Azure RBAC role**
- Allowed actions:
  - View VM details
  - Start virtual machines
  - Stop (deallocate) virtual machines
- Denied permissions for:
  - VM creation or deletion
  - Network or storage modification
  - Any non-VM resource access

---

### 2️⃣ **Role Assignment**

- Assigned the custom role to a user or group
- Scoped the role appropriately:
  - Subscription or Resource Group level
- Verified role visibility and effective permissions

---

### 3️⃣ **Operational Validation**

- Logged in using the assigned identity
- Verified allowed operations:
  - View VM status and details
  - Start VM
  - Stop VM
- Confirmed restricted actions were blocked
- Validated least-privilege enforcement

---

## 🔐 **Security & Governance Configuration**

- Applied **least-privilege access model**
- Used custom RBAC instead of broad built-in roles
- Prevented accidental or unauthorized changes
- Followed Azure governance and monitoring best practices

---

## 📈 **Key Learning Outcomes**

- Azure RBAC role customization
- Monitoring-focused access control
- Secure VM lifecycle operations
- Permission scoping and validation
- Identity and access governance in Azure

---

## 🏆 **Real-World Use Case**

This access model is commonly used for:

- Monitoring and NOC teams
- Operations and support engineers
- Controlled VM lifecycle management
- Compliance-driven environments
- Enterprise cloud operations

---

## 📊 **Outcome**

Successfully created and validated a **custom Azure RBAC role** that enables **monitoring and operational control of virtual machines** while preventing unauthorized changes.

---

## 🛠 **Skills Demonstrated**

- Azure RBAC
- Custom Role Definition
- Azure Virtual Machine Operations
- Monitoring & Operations Governance
- Identity & Access Management (IAM)
- Least Privilege Security Design

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1YdZAbW51GybCueb_8EDh7tQM5aolLuEq/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Monitoring – DevOps Architect Master’s Program (Intellipaat)**
