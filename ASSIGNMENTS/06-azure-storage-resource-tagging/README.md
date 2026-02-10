# 🏷️ Azure Storage Accounts & Resource Tagging

---

## 📌 **Project Overview**

Implemented **Azure resource tagging and governance** by creating multiple Azure Storage Accounts and organizing them using **tags** to represent different teams.

This assignment demonstrates how **tags can be used to logically group, manage, and query Azure resources**, which is essential for cost management, governance, and large-scale enterprise operations.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Storage Accounts**
- **Azure Resource Tags**
- **Azure CLI / Azure PowerShell**
- **Azure Resource Manager (ARM)**

---

## 🎯 **Objective**

To implement tag-based resource management by:

- Creating multiple Azure Storage Accounts
- Applying **Team-based tags** to resources
- Deploying additional resources for a specific team
- Querying and listing resources using tags
- Demonstrating governance-ready Azure resource organization

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Storage Account Creation with Tags**

- Created **three Azure Storage Accounts**
- Assigned **Team tags** as follows:
  - `team = team1`
  - `team = team2`
  - `team = team3`
- Ensured tags were applied at resource creation

---

### 2️⃣ **Additional Storage Account for Team 2**

- Created one more **Azure Storage Account**
- Tagged the resource with:
  - `team = team2`
- Verified correct tag association

---

### 3️⃣ **Resource Listing Using Tags**

- Queried Azure resources using **tag-based filtering**
- Listed all resources associated with:
  - `team = team2`
- Validated results using Azure CLI / PowerShell outputs

---

## 🔐 **Security & Governance Configuration**

- Used tags for logical resource grouping
- Enabled improved cost tracking and ownership identification
- Followed Azure governance best practices
- Prepared resources for role-based access and policy application

---

## 📈 **Key Learning Outcomes**

- Azure resource tagging strategy
- Tag-based resource discovery
- Storage account management
- Azure governance fundamentals
- Resource organization for enterprises
- Cost and ownership tracking using tags

---

## 🏆 **Real-World Use Case**

Resource tagging is widely used for:

- Team-wise cost allocation
- Environment separation (Dev/Test/Prod)
- Enterprise governance and compliance
- Automated reporting and audits
- Managing large Azure subscriptions

---

## 📊 **Outcome**

Successfully created and managed **multiple Azure Storage Accounts** using **team-based tags**, and efficiently listed all resources belonging to **team2**, demonstrating scalable and governance-ready Azure resource management.

---

## 🛠 **Skills Demonstrated**

- Azure Storage Account Management
- Azure Resource Tagging
- Azure CLI
- Azure PowerShell
- Azure Governance & Cost Management
- Resource Discovery & Inventory

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Commands & Screenshots):  
👉 *https://drive.google.com/file/d/1qx7o7b7BWyAAziyQx3kbyVVf1rahRe5g/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Cloud Training – DevOps Architect Master’s Program (Intellipaat)**
