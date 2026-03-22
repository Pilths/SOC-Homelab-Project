# SOC-Homelab-Project
Hybrid between an SOC and Network project implemented within a homelab environment built using open-source toolsused to understand security hardening of devices and protect from simulated attacks.




## Objective
This project was built to simulate a Security Operations Center (SOC) environment for hands-on learning in log monitoring, intrusion detection, and system security hardening.
The goal is to gain practical experience relevant to SOC Analyst and IT Infrastructure internship roles.




## Lab Infrastructure

<p align="center">
  <img src="https://github.com/user-attachments/assets/dcf09fb9-382d-4233-a9fc-4e0eb4de815a"
       alt="Infrastructure Diagram V1"
       width="600">
</p>


## Technologies & Tools Used

### Host Environment
- **Windows 11** – Primary host machine
- **Wazuh Agent** – Endpoint monitoring agent installed on host

### Virtualization Layer
- **VirtualBox**
- **Ubuntu Server 24.04 LTS (Noble Numbat)** with Xubuntu Desktop Environment

### Containerization Platform
- **Docker Engine** – Container runtime environment
- **Portainer** – Web-based Docker management interface

### Security & Monitoring Stack (Current Progress)
- **Wazuh (Single-Node Deployment)** – SIEM platform (Manager, Indexer, Dashboard)
- **Suricata** – Network Intrusion Detection System (IDS)
- **DVWA (Damn Vulnerable Web Application)** – Test web application
- **Nginx Proxy Manager** – Reverse proxy and service routing
- **UFW (Uncomplicated Firewall)** – Host-based firewall configuration

### Security & Monitoring Stack (Current Progress)
- **Suricata** – Network Intrusion Detection System (IDS)
- **DVWA (Damn Vulnerable Web Application)** – Test web application
- **Nginx Proxy Manager** – Reverse proxy and service routing
- **UFW (Uncomplicated Firewall)** – Host-based firewall configuratio

