# 👤 Azure RBAC – User Creation & Custom Role Assignment

---

## 📌 **Project Overview**

Implemented **identity and access management in Azure** by creating a **new user** and assigning a **previously defined custom RBAC role** with limited virtual machine permissions.

This assignment demonstrates how Azure RBAC integrates **user identity management with fine-grained authorization**, enabling secure and controlled access to cloud resources.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Active Directory (Entra ID)**
- **Azure Role-Based Access Control (RBAC)**
- **Custom RBAC Role**
- **Azure Virtual Machines**

---

## 🎯 **Objective**

To securely manage access by:

- Creating a new Azure user
- Assigning the custom RBAC role
- Granting limited VM operational access
- Enforcing least-privilege authorization

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Azure User Creation**

- Created a **new user** in **Azure Active Directory (Entra ID)**
- Assigned appropriate user credentials
- Verified user creation and directory presence

---

### 2️⃣ **Custom Role Assignment**

- Assigned the **previously created custom RBAC role** to the user
- Scoped the role assignment appropriately:
  - Subscription / Resource Group level
- Ensured correct role visibility and binding

---

### 3️⃣ **Access Validation**

- Logged in as the newly created user
- Verified allowed actions:
  - View virtual machines
  - Start virtual machines
  - Stop virtual machines
- Confirmed restricted actions were denied
- Validated RBAC enforcement

---

## 🔐 **Security & Governance Configuration**

- Applied least-privilege access principles
- Used custom RBAC roles instead of broad built-in roles
- Scoped access to minimize blast radius
- Followed Azure IAM best practices

---

## 📈 **Key Learning Outcomes**

- Azure AD (Entra ID) user management
- Custom RBAC role assignment
- Identity-based access control
- Role scope and permission validation
- Secure authorization workflows in Azure

---

## 🏆 **Real-World Use Case**

This approach is commonly used for:

- Delegating limited access to operations teams
- Secure onboarding of new users
- Compliance-driven access management
- Enterprise cloud governance
- Production environment security

---

## 📊 **Outcome**

Successfully created a **new Azure user** and assigned a **custom RBAC role**, enabling controlled VM operations while preventing unauthorized access.

---

## 🛠 **Skills Demonstrated**

- Azure Active Directory (Entra ID)
- Azure RBAC
- User & Role Management
- Identity & Access Management (IAM)
- Cloud Security Governance
- Least Privilege Design

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/14P8KxiB86N7YfGkfNENlxOXnEUnWHKQe/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Authentication & Authorization in Azure – DevOps Architect Master’s Program (Intellipaat)**
