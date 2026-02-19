# Sentient Shield: Enterprise EDR & Threat Hunting Grid 🛡️

**Author:** Dalveer Singh  
**Organization:** Infotact Solutions (Cyber Defense Operations Center)  

## 📖 Project Overview
Infotact's servers face constant brute-force and targeted ransomware attacks. The objective of "Sentient Shield" is to deploy a centralized, real-time system to detect file changes (FIM), monitor critical registry keys, map adversary tactics to the MITRE ATT&CK framework, and execute immediate automated active response actions.

## 🏗️ Architecture
* **SIEM/EDR Core:** Wazuh Manager (All-in-One Deployment)
* **Endpoints:** * Ubuntu 22.04 Web Server (Target)
  * Windows Server (Target) with Sysmon integrated for deep process/network visibility.

## 🚀 Deployment Progress

### Week 1: Infrastructure & Agent Deployment ✅
- [x] Deployed Wazuh Manager on a dedicated Linux server.
- [x] Enrolled Windows and Linux agents.
- [x] Installed and configured Sysmon using SwiftOnSecurity rules.
- **Gate Check Passed:** All agents reporting "Active" status with reliable heartbeats.
  *(Add a screenshot of your Wazuh dashboard showing the 2 active agents here)*