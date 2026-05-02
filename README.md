📌 Overview

This project demonstrates the implementation of a Security Information and Event Management (SIEM) dashboard using the ELK Stack (Elasticsearch, Logstash, and Kibana) for cybersecurity monitoring, threat analysis, and incident investigation.

The dashboard provides real-time visibility into network activities and helps identify suspicious behavior, detect threats, and support security operations.

🎯 Objectives
Monitor and analyze security events in real-time
Detect and investigate cyber threats (DDoS, malware, phishing, etc.)
Visualize log data for better decision-making
Improve incident response and threat detection accuracy

🛠️ Technologies Used
Elasticsearch – Data storage and search engine
Logstash – Log collection and processing
Kibana – Data visualization and dashboard creation
VirusTotal API – Threat intelligence and IP analysis


📊 Dashboard Features

The Kibana dashboard includes multiple visualizations to support security analysis:
🔹 Event Monitoring
Total event count and trends over time
Event severity levels (high to low)
🔹 Threat Detection
Attack types:
DDoS,
Malware,
Ransomware,
Phishing,
SQL Injection,
Brute-force
🔹 Network Analysis
Protocol usage (HTTP, HTTPS, DNS, FTP, SMTP, etc.)
Source and destination IP tracking
Suspicious IP identification
🔹 Geolocation Analysis
Source and destination country mapping
City-based traffic analysis
Detection of abnormal geographic patterns

🔍 Investigation Methodology
The project follows a structured investigation approach:

Log Analysis
Identify unusual patterns in network traffic
Detect anomalies in protocol usage and event frequency
Threat Validation
Cross-check suspicious IPs using VirusTotal
Verify whether alerts are legitimate or false
Alert Classification:
True Positive → Real threat detected
False Positive → Incorrect alert
True Negative → Correctly identified normal activity
False Negative → Missed threat
