# Project 1 - Threat Intelligence Feed Processor
Project: Threat Intelligence Feed Processor
I recently completed a cybersecurity project focused on detecting malicious IP addresses from system log files using a local threat intelligence database.
🔍 Description:
This project simulates a simplified SIEM (Security Information and Event Management) system. It analyzes log files and identifies potentially harmful IPs by comparing them with a database of known malicious addresses.
⚙️ Key Features:
• Stores malicious IPs (IOCs) using SQLite
• Reads and analyzes log files (access.log)
• Matches incoming IPs with threat database
• Generates real-time alerts for suspicious activity
• Supports both live (API-based) and offline demo mode
🛠 Tech Stack:
Python, SQLite
🎯 Objectives:
• Learn log analysis and threat detection
• Gain hands-on experience with databases
• Implement real-time alert generation
🌐 Future Scope:
• Integration with VirusTotal & AlienVault OTX
• Advanced log parsing (firewall/web logs)
• Real-time monitoring dashboard
• Alerts via Email/Telegram
