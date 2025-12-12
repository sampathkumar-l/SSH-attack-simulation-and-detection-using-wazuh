# SSH-attack-simulation-and-detection-using-wazuh
# 🔐 Wazuh SIEM – Windows SSH Brute Force Detection Lab

This project demonstrates how Wazuh SIEM detects brute-force attacks performed against a Windows 10 machine using SSH.  
Wazuh captures Windows Event Logs (EventID 4625/4624) and maps the activity to MITRE ATT&CK techniques such as:

- **T1110 – Brute Force**
- **T1078 – Valid Accounts**

This lab was created using:
- **Ubuntu Server** (Wazuh Manager + Dashboard)
- **Windows 10 VM** (Wazuh Agent)
- **Attacker machine (Ubuntu/Kali)**

---

## 🏗️ Lab Architecture
