# 👥 Azure RBAC – Group-Based Role Assignment & Permission Validation

---

## 📌 **Project Overview**

Implemented **group-based access control using Azure RBAC** by creating a **user group**, assigning a **custom RBAC role** to the group, and validating permission inheritance for group members.

This assignment demonstrates how Azure supports **scalable and maintainable access management** using groups instead of assigning roles individually to users.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Active Directory (Entra ID)**
- **Azure RBAC**
- **User Group**
- **Custom RBAC Role**
- **Azure Virtual Machines**

---

## 🎯 **Objective**

To design a scalable authorization model that:

- Creates a user group
- Assigns a custom RBAC role to the group
- Adds users to the group
- Automatically grants permissions to all group members
- Validates group-based permission inheritance

---

## ⚙️ **Implementation Steps**

### 1️⃣ **User Group Creation**

- Created a **user group** in **Azure Active Directory (Entra ID)**
- Defined group name and membership type
- Verified successful group creation

---

### 2️⃣ **Custom Role Assignment to Group**

- Assigned the **custom RBAC role** (created in Assignment 1) to the group
- Scoped the role assignment appropriately:
  - Subscription / Resource Group level
- Verified role assignment visibility

---

### 3️⃣ **User Membership & Permission Validation**

- Added **new users** to the group
- Logged in as group members
- Verified inherited permissions:
  - View virtual machines
  - Start virtual machines
  - Stop virtual machines
- Confirmed restricted actions were blocked

---

## 🔐 **Security & Governance Configuration**

- Used group-based RBAC instead of individual assignments
- Reduced administrative overhead
- Ensured consistent permission enforcement
- Followed least-privilege access principles

---

## 📈 **Key Learning Outcomes**

- Azure AD (Entra ID) group management
- Group-based RBAC role assignment
- Permission inheritance and validation
- Scalable identity and access management
- Secure cloud governance practices

---

## 🏆 **Real-World Use Case**

Group-based RBAC is widely used for:

- Managing team-level permissions
- Enterprise IAM governance
- Secure onboarding and offboarding
- Role-based access enforcement
- Compliance and audit readiness

---

## 📊 **Outcome**

Successfully implemented **group-based access control** by assigning a **custom RBAC role** to a user group and validating **automatic permission inheritance** for all group members.

---

## 🛠 **Skills Demonstrated**

- Azure Active Directory (Entra ID)
- Azure RBAC
- Group-Based Access Control
- Identity & Access Management (IAM)
- Cloud Security Governance
- Least Privilege Architecture

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1TcpecX5Nvu6hrTrxKulJ9ezA041whoDH/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Authentication & Authorization in Azure – DevOps Architect Master’s Program (Intellipaat)**
