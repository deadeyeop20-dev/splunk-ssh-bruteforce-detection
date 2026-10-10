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
