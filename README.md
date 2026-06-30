# 🛡️ Wazuh + Shuffle SOAR Automated Incident Response

## 📌 Overview

This project demonstrates an automated Security Operations (SecOps) workflow using Wazuh SIEM, Shuffle SOAR, Docker, Python, and Sophos Firewall.

The workflow automatically detects brute-force attacks through Wazuh, triggers a Shuffle SOAR playbook, and blocks the attacker's IP address on Sophos Firewall using its REST API.

This project aims to reduce manual incident response time and improve security automation.

---

## 🚀 Features

- Detect SSH brute-force attacks using Wazuh
- Trigger automated workflows using Shuffle SOAR
- Block attacker IP automatically on Sophos Firewall
- Integrate using REST APIs
- Deploy services using Docker
- Automate incident response
- Improve SOC efficiency

---

## 🛠️ Technologies Used

- Wazuh SIEM
- Shuffle SOAR
- Sophos Firewall API
- Docker & Docker Compose
- Python
- Linux
- REST API
- Webhooks

---

## 📂 Project Structure

```
SOAR-Automation/
│
├── docker-compose.yml
├── README.md
├── workflows/
├── scripts/
├── screenshots/
├── architecture/
└── docs/
```

---

## 🔄 Workflow

```
Attacker
    │
    ▼
Target Machine
    │
    ▼
Wazuh SIEM
    │
    ▼
Shuffle SOAR
    │
    ▼
Python Script
    │
    ▼
Sophos Firewall API
    │
    ▼
Block Attacker IP
```

---

## 📸 Screenshots

### Architecture Diagram

(Add image here)

### Shuffle Workflow

(Add image here)

### Wazuh Alerts

(Add image here)

### Sophos Firewall Rule

(Add image here)

---

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Wazuh-Shuffle-SOAR-Automation.git
```

2. Navigate to the project

```bash
cd Wazuh-Shuffle-SOAR-Automation
```

3. Configure your environment variables.

4. Start Docker containers.

```bash
docker compose up -d
```

---

## 🧪 Testing

Generate a brute-force attack.

Verify that:

- Wazuh generates an alert.
- Shuffle receives the webhook.
- Python executes successfully.
- Sophos Firewall blocks the source IP.

---

## 🔮 Future Improvements

- Email Notifications
- Slack Integration
- Microsoft Teams Integration
- VirusTotal Integration
- Threat Intelligence Feeds
- AI-assisted Incident Classification

---

## 👥 Contributors

- Ahmed Essam
- Mahmoud Samy

---

## 📄 License

This project is for educational and research purposes.
