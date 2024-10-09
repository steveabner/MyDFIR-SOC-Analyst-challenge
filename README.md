# This project is ongoing and will be updated as I progress

# MyDFIR-SOC-Analyst-challenge

## Introduction

This document outlines my participation in the MyDFIR 30-Day SOC Analyst Challenge, created by Steven at MyDFIR.com. This free initiative aims to equip aspiring SOC analysts with practical skills over a 30-day period.

## Day 1
On Day 1, I developed a logical diagram using draw.io to illustrate the network architecture for this challenge.

The diagram features a VULTR VPC comprising six servers:

- Windows Server (RDP Enabled)
- Ubuntu Server (SSH Enabled)
- Fleet Server
- Elastic & Kibana Server
- osTicket Server
- C2 Server

![30day-MyDFIR-Diagram drawio](https://github.com/user-attachments/assets/98019d97-aff6-4206-ad70-0665732799a6)
<!--Logs from the Windows and Ubuntu servers will be forwarded to the Elastic & Kibana server via designated agents.


---

<details>
<summary> </summary>
