# This project is ongoing and will be updated as I progress

# MyDFIR-SOC-Analyst-challenge
![30day-MyDFIR-Diagram drawio (1)](https://github.com/user-attachments/assets/bb4a515f-daf4-415f-89c0-38308d4de41d)
## Introduction

In this challenge, I will be doing the MyDFIR 30-Day SOC Analyst Challenge by Steven at MyDFIR.com

This is a free challenge that Steven created for aspiring SOC analysts. It was designed to help newbies obtain practical skills in 30 days.

On Day 1 I created a logical diagram using draw.io

The Logical Diagram will utilize a VULTR VPC and consist of 6 servers:
- Windows Server (RDP Enabled)
- Ubuntu Server (SSH Enabled)
- Fleet Server 
- Elastic & Kibana Server
- osTicket Server
- C2 Server

The logs from the windows and ubuntu server's will be forwarded to the elastic & kibana server via agents

---

<details>
<summary>Creating the OpenVAS VM in Azure</summary>
  
---
  
To begin, I will access the Azure portal to configure a new virtual machine for the OpenVAS Vulnerability Management Scanner.

Within the Azure portal, I will navigate to the "Marketplace" and select it.
