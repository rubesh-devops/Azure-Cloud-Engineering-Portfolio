# 🔑 Azure RBAC – Custom Role for Virtual Machine Operations

---

## 📌 **Project Overview**

Implemented **role-based access control (RBAC)** in Azure by creating a **custom role** that allows users to **view, start, and stop virtual machines**, while explicitly **restricting all other permissions**.

This assignment demonstrates fine-grained access control in Azure, ensuring **least-privilege security** for operational roles.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Role-Based Access Control (RBAC)**
- **Azure Virtual Machines**
- **Custom Role Definition**
- **Azure Active Directory (Entra ID)**

---

## 🎯 **Objective**

To design a secure authorization model that:

- Grants limited VM operational access
- Allows users to:
  - View VM details
  - Start virtual machines
  - Stop virtual machines
- Prevents all other resource modifications
- Enforces the principle of least privilege

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Custom RBAC Role Definition**

- Created a **custom Azure RBAC role**
- Allowed permissions:
  - Read virtual machine details
  - Start virtual machines
  - Stop (deallocate) virtual machines
- Explicitly excluded permissions for:
  - VM creation or deletion
  - Network, storage, or configuration changes
  - Any non-VM resources

---

### 2️⃣ **Role Assignment**

- Assigned the custom role to a user or group
- Scoped the role assignment appropriately:
  - Subscription / Resource Group level
- Verified role visibility and assignment

---

### 3️⃣ **Permission Validation**

- Logged in as the assigned user
- Verified allowed actions:
  - View VM details
  - Start VM
  - Stop VM
- Confirmed restricted actions were blocked
- Validated effective RBAC enforcement

---

## 🔐 **Security & Governance Configuration**

- Applied **least privilege access**
- Used custom RBAC instead of built-in broad roles
- Prevented accidental or unauthorized changes
- Followed Azure security best practices

---

## 📈 **Key Learning Outcomes**

- Azure RBAC fundamentals
- Custom role creation
- Fine-grained permission control
- Role assignment and scope management
- Secure access governance in Azure
- Identity and access management (IAM)

---

## 🏆 **Real-World Use Case**

Custom RBAC roles are widely used for:

- Operations teams managing VM lifecycle
- Helpdesk or support access control
- Compliance-driven access models
- Secure enterprise cloud environments
- Delegated administration

---

## 📊 **Outcome**

Successfully created and validated a **custom Azure RBAC role** that allows **viewing, starting, and stopping virtual machines only**, enforcing strict access boundaries.

---

## 🛠 **Skills Demonstrated**

- Azure RBAC
- Custom Role Definitions
- Identity & Access Management
- Virtual Machine Lifecycle Control
- Azure Security Governance
- Least Privilege Design

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1n6Nz2iHT9ZboGTZhT7bmqZw4rebX_1ki/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Authentication & Authorization in Azure – DevOps Architect Master’s Program (Intellipaat)**
