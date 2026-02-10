# 🌍 Azure DNS – Custom Domain Mapping to Azure Virtual Machine

---

## 📌 **Project Overview**

Configured a **custom domain name** to point to an **Azure Virtual Machine hosting an Apache2 web server** using **Azure DNS**.

This assignment demonstrates how Azure DNS can be used to manage **public DNS records** and map custom domains to cloud-hosted applications, enabling professional and user-friendly access to services.

---

## 🏗 **Architecture Components**

- **Microsoft Azure**
- **Azure Virtual Machine (Linux – Ubuntu)**
- **Apache2 Web Server**
- **Azure DNS**
- **Public IP Address**
- **Custom Domain (Freenom)**
- **DNS A Record**

---

## 🎯 **Objective**

To enable domain-based access to an Azure-hosted application by:

- Reusing an existing Apache2-enabled Linux VM
- Acquiring a free custom domain
- Creating a DNS zone in Azure DNS
- Mapping the domain to the VM’s public IP address
- Verifying successful website access via domain name

---

## ⚙️ **Implementation Steps**

### 1️⃣ **Reuse Existing Apache2 VM**

- Used the previously created **Linux VM with Apache2 installed**
- Verified web server functionality using public IP
- Ensured VM was accessible over HTTP (Port 80)

---

### 2️⃣ **Domain Acquisition**

- Obtained a **free domain** from **freenom.com**
- Verified domain ownership and availability
- Prepared domain for DNS configuration

---

### 3️⃣ **Azure DNS Zone Configuration**

- Created a **DNS Zone** in **Azure DNS**
- Added required **Name Server (NS)** records
- Updated domain name servers in Freenom to point to Azure DNS

---

### 4️⃣ **DNS Record Mapping**

- Created an **A Record** in Azure DNS
- Mapped the domain name to the VM’s **public IP address**
- Verified DNS record propagation

---

### 5️⃣ **Domain Access Verification**

- Accessed the website using the **custom domain name**
- Confirmed successful loading of the Apache2 default page
- Validated end-to-end DNS resolution and web access

---

## 🔐 **Security & Governance Configuration**

- Restricted VM access using **Network Security Groups**
- Exposed only **HTTP (Port 80)** publicly
- Used Azure-managed DNS services
- Followed best practices for public-facing web applications

---

## 📈 **Key Learning Outcomes**

- Azure DNS configuration and management
- Domain name system (DNS) fundamentals
- Custom domain mapping to cloud resources
- Public IP-based service exposure
- End-to-end web application accessibility
- Azure networking and hosting integration

---

## 🏆 **Real-World Use Case**

Custom domain mapping using Azure DNS is commonly used for:

- Hosting public websites
- Branding cloud-hosted applications
- SaaS product deployment
- Startup and enterprise web services
- Production-ready application access

---

## 📊 **Outcome**

Successfully mapped a **custom domain name** to an **Azure Virtual Machine running Apache2**, enabling domain-based access to the web application using **Azure DNS**.

---

## 🛠 **Skills Demonstrated**

- Azure DNS
- Domain Name Management
- DNS Record Configuration
- Azure Virtual Machines
- Apache2 Web Server
- Public IP Networking
- Cloud Hosting Fundamentals

---

## 📸 **Proof of Implementation**

📄 Consolidated Assignment Execution PDF (Screenshots & Validation):  
👉 *https://drive.google.com/file/d/1xYNCf6J8lnavN4nwclxBagMY6Z5a9XgG/view?usp=drive_link*

---

## 📚 **Course Reference**

Assignment completed as part of:

**Azure Networking – DevOps Architect Master’s Program (Intellipaat)**
