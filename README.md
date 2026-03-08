# SOC-DNS-Log-Analysis
SOC home lab project - DNS log analysis using Splunk SIEM
# SOC DNS Log Analysis Project

## Overview
Analyzed DNS log files using Splunk Enterprise SIEM to identify compromised 
hosts communicating with malicious Command & Control (C2) domains.

## Tools Used
- Splunk Enterprise 10.2.1
- Kali Linux (VirtualBox)
- SPL (Splunk Processing Language)

## What I Did
- Set up Splunk SIEM on Kali Linux home lab
- Loaded DNS log data into Splunk
- Wrote SPL queries to detect suspicious domains
- Identified 2 compromised hosts
- Created visualizations of malicious traffic
- Wrote professional incident report

## Key Findings
- 2 internal hosts contacting C2 server (malware-c2.ru)
- 3 malicious domains identified
- NXDOMAIN responses indicating C2 beacon attempts

## Files
- `SOC_Incident_Report.docx` - Full incident report
- `screenshots/` - Splunk query results and visualizations
