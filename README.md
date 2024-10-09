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

## Day 2
On Day 2, I learned about the ELK STACK
- Elasticsearch
- Logstash
- Kibana

### Elasticsearch 
- I will use Elasticsearch to store Windows event logs, syslogs, and firewall logs, enabling real-time analysis of large data volumes. It is often paired with Kibana, which helps visualize the data for improved insights.

### Logstash
-Logstash is an open-source tool that collects and processes data from various sources, like logs and events. It’s part of the Elastic Stack and works well with Elasticsearch. You can use Logstash to gather data, transform it, and send it to Elasticsearch, making it easier to analyze and visualize your logs with Kibana. It's a great way to get clear insights from your data!
<!--Logs from the Windows and Ubuntu servers will be forwarded to the Elastic & Kibana server via designated agents.


---

<details>
<summary> </summary>
