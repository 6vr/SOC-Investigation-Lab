# Windows SOC Investigation Lab

## Overview
This lab simulates a realistic Windows-based cyber incident investigation. The analysis utilizes **Splunk** for log analysis and **Wireshark** for network traffic inspection. Additionally, Sigma rules are applied for threat detection.

## Contents
- **`data/`**: Contains sample Windows Security and Sysmon logs, and a placeholder for network capture data.
- **`rules/`**: Sigma rule designed to detect suspicious PowerShell executions indicative of attacks.
- **`report/`**: Professionally documented incident report summarizing findings.

## How to Use
1. **Import** the log files from the `data/` directory into Splunk for ingestion and analysis.  
2. **Apply** the Sigma rule located at `rules/suspicious_powershell.yml` to detect suspicious activities.  
3. **Analyze** network traffic using Wireshark with your own PCAP file, replacing the placeholder if necessary.  
4. **Review** the detailed incident report found in `report/Incident_Report.pdf`.

## Tools Utilized
- **Splunk**: Powerful platform for searching, monitoring, and analyzing machine-generated data.  
- **Wireshark**: Network protocol analyzer for deep inspection of live or captured network traffic.  
- **Sigma**: Generic and open signature format for SIEM systems, enabling platform-independent detection.

---

*This lab is intended for educational and demonstration purposes only.*
