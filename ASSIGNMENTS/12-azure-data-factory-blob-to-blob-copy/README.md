# 🔄 Azure Data Factory – Blob-to-Blob Data Copy Pipeline

---

## 📌 **Project Overview**

Implemented a **data movement pipeline using Azure Data Factory (ADF)** to copy data between **two Azure Blob Storage accounts**.

This assignment demonstrates how **Azure Data Factory enables scalable, managed data integration** for moving data across storage services without manual intervention, a core requirement in modern data platforms.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Storage Account (Source)**
- **Azure Storage Account (Destination)**
- **Azure Blob Containers**
- **Azure Data Factory**
- **ADF Copy Activity**
- **Azure Resource Manager (ARM)**

---

## 🎯 **Objective**

To design and execute a data integration workflow that:

- Creates multiple Azure Storage Accounts
- Uploads data to a source Blob container
- Uses **Azure Data Factory** to copy data
- Transfers data securely to a destination Blob container
- Demonstrates managed, scalable data movement

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Storage Account & Container Setup**

- Created **two Azure Storage Accounts**
- Created a **Blob container** inside each storage account
- Verified container availability and access

---

### 2️⃣ **Source Data Upload**

- Uploaded sample data to the **source Blob container**
- Verified data presence and structure
- Prepared the data for transfer

---

### 3️⃣ **Azure Data Factory Configuration**

- Created an **Azure Data Factory instance**
- Configured **linked services** for:
  - Source Storage Account
  - Destination Storage Account
- Defined **datasets** for source and destination containers

---

### 4️⃣ **Data Copy Using ADF**

- Created a **Copy Data pipeline**
- Used **ADF Copy Activity** to transfer data
- Executed the pipeline
- Verified successful data copy to destination container

---

## 🔐 **Security & Governance Configuration**

- Used Azure-managed authentication for ADF
- Applied least-privilege access to storage resources
- Ensured secure data transfer between services
- Followed Azure best practices for data integration security

---

## 📈 **Key Learning Outcomes**

- Azure Data Factory fundamentals
- Blob-to-Blob data transfer
- Linked services and datasets
- Managed data pipelines
- Cloud data integration concepts
- Secure and scalable data movement

---

## 🏆 **Real-World Use Case**

Azure Data Factory is commonly used for:

- Data migration between storage accounts
- ETL and ELT workflows
- Data lake ingestion pipelines
- Cross-environment data synchronization
- Enterprise data integration solutions

---

## 📊 **Outcome**

Successfully copied data from one **Azure Blob Storage account** to another using **Azure Data Factory**, validating a **fully managed, scalable data integration pipeline**.

---

## 🛠 **Skills Demonstrated**

- Azure Data Factory
- Azure Blob Storage
- Data Integration Pipelines
- ADF Copy Activity
- Linked Services & Datasets
- Cloud Data Engineering Fundamentals
- Azure Resource Management

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1_VSMxIDQicJz3b0wfr4HlVA60NJIkJq2/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Cloud Training – DevOps Architect Master’s Program (Intellipaat)**
