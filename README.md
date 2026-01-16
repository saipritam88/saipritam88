# Roboshop Infrastructure Automation – Ansible + AWS

This repository contains complete automation for deploying the **Roboshop Microservices Application** using **Ansible**, **AWS EC2**, and **Route53 DNS**.

The entire infra provisioning + configuration is automated end-to-end.

---

## 🚀 What this project does

| Stage | Automated? | Description |
|-------|------------|-------------|
| Provision EC2 Instances | ✅ | Creates all required servers using Ansible + AWS modules |
| Route53 DNS Records | ✅ | Automatically creates A Records for each instance |
| Application Configuration | ✅ | Installs packages, copies code, sets services |
| MySQL remote access setup | ✅ | Allows remote DB usage for app services |
| Application deployment | ✅ | Deploys & configures all microservices |

---

## Components Configured

| Service | Tech Stack |
|--------|------------|
| MongoDB | NoSQL database |
| MySQL | Relational DB + Root remote access |
| Catalogue | NodeJS |
| User | NodeJS |
| Cart | NodeJS |
| Shipping | Java + Maven |
| Payment | Python |
| RabbitMQ | Messaging queue |
| Redis | Cache |
| Web | Nginx reverse proxy |

---

## Key Features

- Fully idempotent Ansible Playbooks
- EC2 instance creation automated
- DNS records creation (Route53)
- Every server configured through YAML

---

## Tools Used

| Category | Tools |
|----------|-------|
| Provisioning & Config | Ansible |
| Cloud Provider | AWS EC2 |
| DNS | Route53 |
| Source Control | GitHub |
| Package Managers | npm / pip / maven |

---
<img width="1909" height="688" alt="image" src="https://github.com/user-attachments/assets/a5383293-5018-43a6-bd62-e21342153440" />

<img width="1910" height="962" alt="image" src="https://github.com/user-attachments/assets/3a981aaa-9384-4673-85fe-004dcce25343" />

<img width="1892" height="541" alt="image" src="https://github.com/user-attachments/assets/3d6de1e6-f193-4426-95da-979c32db6789" />

