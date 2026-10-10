# Splunk SSH Brute-Force Detection and Incident Response

## Project Overview
This project demonstrates how to simulate an SSH brute-force attack in a controlled virtual lab, monitor security logs using Splunk SIEM, and respond by blocking the attacker's IP address.

# Tools and Technologies
- Splunk Enterprise — Security log monitoring and analysis
- Splunk Universal Forwarder** — Log collection and forwarding
- Ubuntu Server — SSH server and Splunk environment
- Kali Linux — Attack simulation using Hydra
- pfSense — Network security and log reporting
- Windows — Additional log collection using Universal Forwarder

# Project Workflow
1. Installed and configured Ubuntu Server.
2. Installed Splunk Enterprise and configured network access.
3. Installed and configured Splunk Universal Forwarders on Windows and Ubuntu.
4. Installed and configured pfSense, including WAN and LAN interfaces.
5. Configured SSH on the Ubuntu server.
6. Used Hydra with a password list to simulate SSH brute-force attempts in the lab.
7. Monitored and investigated relevant logs in Splunk.
8. Blocked the attacker's IP address as an incident response measure.

# Learning Outcomes
- SIEM deployment and log monitoring
- Log forwarding and collection
- SSH brute-force attack simulation
- Security event investigation
- Basic incident response and IP blocking

# Disclaimer
This project was performed in a controlled lab environment for educational purposes. Attack simulations should only be conducted on systems you own or have explicit permission to test.

# Network Architecture

The lab consists of multiple virtual machines and security components working together to simulate, monitor, and respond to SSH brute-force activity.

**Components:**
- Kali Linux: Generates controlled SSH brute-force test traffic using Hydra.
- Ubuntu Server: Hosts the SSH service and Splunk Enterprise.
- Windows: Sends selected system logs through Splunk Universal Forwarder.
- Ubuntu Universal Forwarder: Collects and forwards configured logs.
- pfSense: Provides network security controls and IP-blocking functionality.
- Splunk Enterprise: Receives and analyzes logs for security investigation.

Workflow: Attack Simulation → Log Collection → Splunk Investigation → IP Blocking → Response Validation

# Project Screenshots

# 1. Splunk Enterprise
![Splunk Enterprise](screenshots/01-splunk-enterprise.png)

# 2. SSH Log Ingestion
![SSH Log Ingestion](screenshots/02-ssh-log-ingestion.png)

# 3. pfSense Configuration
![pfSense Configuration](screenshots/03-pfsense-configuration.png)

# 4. Hydra Attack Simulation
![Hydra Attack Simulation](screenshots/04-hydra-simulation.png)

# 5. Splunk Detection Results
![Splunk Detection Results](screenshots/05-spl-detection-results.png)

# 6. IP Blocking Rule
![IP Blocking Rule](screenshots/06-ip-block-rule.png)

# 7. Response Validation
![Response Validation](screenshots/07-07-response-validation.png)
