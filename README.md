# This project is ongoing and will be updated as I progress

# MyDFIR-SOC-Analyst-challenge
![30day-MyDFIR-Diagram drawio (1)](https://github.com/user-attachments/assets/bb4a515f-daf4-415f-89c0-38308d4de41d)
## Introduction

This document outlines my participation in the MyDFIR 30-Day SOC Analyst Challenge, created by Steven at MyDFIR.com. This free initiative aims to equip aspiring SOC analysts with practical skills over a 30-day period.

On Day 1, I developed a logical diagram using draw.io to illustrate the network architecture for this challenge.

The diagram features a VULTR VPC comprising six servers:

- Windows Server (RDP Enabled)
- Ubuntu Server (SSH Enabled)
- Fleet Server
- Elastic & Kibana Server
- osTicket Server
- C2 Server
  
Logs from the Windows and Ubuntu servers will be forwarded to the Elastic & Kibana server via designated agents.

---

<!--<details>
<summary>Creating the OpenVAS VM in Azure</summary>
  
---
  
To begin, I will access the Azure portal to configure a new virtual machine for the OpenVAS Vulnerability Management Scanner.

Within the Azure portal, I will navigate to the "Marketplace" and select it. 

--!>
