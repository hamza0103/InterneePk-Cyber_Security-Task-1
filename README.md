# InterneePk-Cyber_Security-Task-1
# Task 1: Endpoint Security & Monitoring
**Intern:** Muhammad Hamza Hayat
**Domain:** Cyber Security @ Internee.pk

## 📌 Project Objective
To secure a corporate endpoint by deploying an EDR solution (Wazuh) and integrating advanced log monitoring (Sysmon) to detect potential threats.

## 🛠️ Implementation Steps
1. **Server Setup:** Deployed Wazuh Manager on Kali Linux (Virtual Machine).
2. **Agent Deployment:** Installed Wazuh Agent on a remote Windows 10 Endpoint.
3. **Log Integration:** Configured `ossec.conf` to ingest Sysmon logs (EventChannel).
4. **Threat Simulation:** Executed reconnaissance commands (`whoami`, `net user`, `ipconfig`) to verify detection.

## 📸 Proof of Work

### 1. Sysmon Installation (Endpoint)
Successfully installed Sysmon with SwiftOnSecurity configuration to filter system noise.
![Sysmon Install](Screenshot%202026-01-21%20194146.png)

### 2. Agent Connection Status
The Windows Endpoint is successfully connected and Active on the Wazuh Dashboard.
![Agent Status](Screenshot%202026-01-21%20195501.png)

### 3. Threat Hunting & Log Analysis
Real-time detection of executed commands (`ipconfig`, `whoami`) captured by the Wazuh Manager.
![Threat Hunting](Screenshot%202026-01-21%20201026.png)
