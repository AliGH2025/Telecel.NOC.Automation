# Telecel.NOC.Automation

**Designed and developed by Ali Abdallah**

---

## ⚙️ Overview
Telecel.NOC.Automation is a backend automation and integration platform built using .NET 8 and Clean Architecture principles.  
It automates the monitoring and testing workflow of telecom network operations by connecting multiple systems and APIs in real time.

This repository provides a **high-level overview** of the solution and its architecture for professional presentation.  
No operational code, data, or configuration files are included.

---

## 🎯 Objective
The platform replaces manual NOC monitoring tasks with automated processes that:
- Detect and process network alerts from email sources  
- Enrich alerts with routing and vendor information from API integrations  
- Trigger automated test procedures through external testing systems  
- Log and monitor results for KPI tracking and reporting

---

## 🔗 Integrations
Telecel.NOC.Automation communicates with several APIs and services:
- **Microsoft Graph** → receives and parses NOC alert emails via webhook  
- **Alaris REST API** → retrieves route, vendor, and client data  
- **Testelium API** → triggers and monitors automated SMS route tests  
- **Excel Service** → processes telecom prefix mappings and data configurations

---

## 🧩 System Architecture (Conceptual)
The system follows a multi-layered clean architecture pattern:



This ensures maintainability, scalability, and testability for future microservice expansion.

---

## 🛠️ Technologies
- .NET 8 / C#  
- ASP.NET Core Web API  
- Microsoft Graph SDK  
- HttpClient + Polly resilience  
- REST API Integrations  
- Docker (intro)  
- Clean Architecture principles  

---

## 💡 Key Benefits
- Reduces manual alert handling by automating detection and testing  
- Improves operational efficiency and accuracy  
- Enables continuous performance validation through real-time testing  
- Provides structured, extensible backend for future integrations  

---

## 👤 Author
**Ali Abdallah**  
Senior .NET Developer | API Integrations & Automation | ASP.NET Core | SQL Server | Clean Architecture  
[LinkedIn Profile](https://www.linkedin.com/in/aliabdallah-dotnet/)

---

## ⚠️ Disclaimer
This repository is for **portfolio and demonstration purposes only**.  
All operational rights, source code, and data remain the property of **Telecel Global**.


