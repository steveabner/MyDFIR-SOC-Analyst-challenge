# This project is ongoing and will be updated as I progress

# MyDFIR-SOC-Analyst-challenge

## Introduction

This page outlines my participation in the MyDFIR 30-Day SOC Analyst Challenge, created by Steven at MyDFIR.com. This free initiative aims to equip aspiring SOC analysts with practical skills over a 30-day period.

Check out Steven's Youtube playlist here [30-Day MyDFIR SOC Analyst Challenge!](https://www.youtube.com/watch?v=W3ExS2m6B24&list=PLG6KGSNK4PuBb0OjyDIdACZnb8AoNBeq6&index=1)

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
On Day 2, I learned about the ELK STACK:
- E - Elasticsearch
- L - Logstash
- K - Kibana

### Elasticsearch 
- I will use Elasticsearch to store logs, including Windows event logs, syslogs, and firewall logs, allowing for real-time analysis of large data volumes. It’s often used with Kibana, which visualizes the data for better insights.

### Logstash
- Logstash is an open-source tool that collects and processes data from various sources, such as logs and events. I will use Logstash with Elastic Agents to gather, transform, and send data to Elasticsearch, simplifying the analysis and visualization of logs with Kibana.

### Kibana
- Using Kibana with Elasticsearch will allow me to explore, analyze, and visualize data through interactive dashboards and real-time graphs.


## Day 3
On Day 3, I registered for a VULTR account. In the VULTR dashboard, I set up a Virtual Private Cloud (VPC) and created an Ubuntu 22.04 Virtual Machine.

![2024-10-09 16_38_14-Window](https://github.com/user-attachments/assets/e75c0d8c-5e7b-482e-9e7d-48cd7b2b574c)

---

After setting up the Ubuntu Virtual Machine, I accessed it via SSH and installed Elasticsearch.

![2024-10-09 16_45_20-root@MyDFIR-ELK_ _](https://github.com/user-attachments/assets/e461d8ec-8a5d-4f4b-9266-e3e2fe100a49)

---

With Elasticsearch installed, I need to edit the configuration file to ensure accessibility by adjusting the "Network Host" and "HTTP Port." The network host will be set to the IP address of the Ubuntu VM.

![2024-10-09 16_50_26-root@MyDFIR-ELK_ _etc_elasticsearch](https://github.com/user-attachments/assets/20331012-924f-492c-8add-84f4a25bb295)
![2024-10-09 16_55_02-root@MyDFIR-ELK_ _etc_elasticsearch](https://github.com/user-attachments/assets/40ed1fcf-31e4-4c0b-b1b7-a1cd48c8f30f)

---

Finally, to prevent unauthorized access to my Elasticsearch from the entire internet, I'll tighten the firewall rules to allow access only from my specific IP address.

![2024-10-09 17_08_06-Manage Firewall - Vultr com](https://github.com/user-attachments/assets/91d4a457-910f-44e2-8c0a-d3774e318ebc)

---

<!--Logs from the Windows and Ubuntu servers will be forwarded to the Elastic & Kibana server via designated agents.


---

<details>
<summary> </summary>
