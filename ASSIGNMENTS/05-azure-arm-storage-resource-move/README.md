# 📦 Azure ARM & Storage Account Resource Management

---

## 📌 **Project Overview**

Implemented **Azure Resource Manager (ARM)–based resource management** by creating multiple resource groups, deploying an Azure Storage Account, and performing a **resource move operation across resource groups**.

This assignment demonstrates how Azure enables **logical separation, governance, and flexibility** by allowing resources to be moved without redeployment—an important capability for restructuring environments and cost management.

---

## 🏗 **Architecture Components**

- **Azure Resource Manager (ARM)**
- **Azure Resource Groups**
- **Azure Storage Account**
- **Azure Portal / CLI / PowerShell**
- **Azure Subscription**

---

## 🎯 **Objective**

To perform ARM-based resource management tasks that:

- Create and manage multiple **Azure Resource Groups**
- Deploy an **Azure Storage Account**
- Move a resource between resource groups
- Demonstrate Azure’s flexible resource lifecycle management

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Resource Group Creation**

- Created two Azure Resource Groups:
  - **rg-1**
  - **rg-2**
- Ensured both resource groups were created successfully
- Verified resource groups via Azure Portal and CLI/PowerShell

---

### 2️⃣ **Storage Account Deployment**

- Created an **Azure Storage Account**
- Deployed the storage account inside:
  - **Resource Group:** `rg-1`
- Verified successful provisioning and availability

---

### 3️⃣ **Resource Move Operation**

- Initiated a **resource move** operation using ARM
- Moved the storage account:
  - From **rg-1**
  - To **rg-2**
- Validated that the storage account:
  - Retained configuration
  - Remained accessible after the move

---

## 🔐 **Security & Governance Configuration**

- Used ARM-based permissions for resource movement
- Ensured correct subscription and role access
- Maintained resource-level governance during the move
- Followed Azure best practices for resource organization

---

## 📈 **Key Learning Outcomes**

- Azure Resource Manager (ARM) fundamentals
- Resource group design and usage
- Azure Storage Account deployment
- Resource move operations across resource groups
- Azure governance and lifecycle management
- Non-disruptive infrastructure reorganization

---

## 🏆 **Real-World Use Case**

This approach is commonly used for:

- Environment restructuring (Dev → Prod)
- Cost and billing reorganization
- Subscription and resource governance
- Cloud migration and refactoring
- Enterprise Azure environment management

---

## 📊 **Outcome**

Successfully created multiple resource groups, deployed an Azure Storage Account, and **moved the resource between resource groups without downtime**, demonstrating Azure ARM’s flexibility and control.

---

## 🛠 **Skills Demonstrated**

- Azure Resource Manager (ARM)
- Azure Resource Group Management
- Azure Storage Account
- Resource Lifecycle Operations
- Cloud Governance
- Azure Infrastructure Administration

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Commands & Screenshots):  
👉 *https://drive.google.com/file/d/1qx7o7b7BWyAAziyQx3kbyVVf1rahRe5g/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Cloud Training – DevOps Architect Master’s Program (Intellipaat)**

