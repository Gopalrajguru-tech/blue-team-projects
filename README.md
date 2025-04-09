# blue-team-projects
A collection of hands-on blue team projects featuring a custom home lab setup and tools like Snort, Suricata, ELK Stack, and Splunk. Includes work on intrusion detection, log analysis, threat monitoring, and SIEM dashboards to demonstrate core cybersecurity defense skills.

# 🔵 Blue Team Cybersecurity Projects

This repository contains a collection of hands-on Blue Team cybersecurity projects focused on detection, monitoring, and incident analysis. It includes real-world configurations and labs involving SIEMs, IDS/IPS, and log management tools, implemented in both on-premises and cloud environments.

## 📂 Project List

### 1. 🏠 Home Lab Setup
A virtual enterprise-like network designed for blue teaming, threat detection, and malware analysis practice.
- Tools: pfSense, Kali Linux, Windows Server 2019, Active Directory, Metasploitable, Windows 10, Zeek
- Features: Internal segmentation, firewall rules, DHCP/DNS, vulnerable AD environment, simulated attacks

📄 [Read Full Documentation](./HOMELAB%20SETUP.pdf)

---

### 2. 🛑 Snort IDS
Setup and customization of Snort for real-time packet inspection and alerting based on network rules.
- Installed on Ubuntu VM
- Configured with custom rules to detect Nmap scans, ICMP floods, UDP floods, etc.
- Real-time alerts for reconnaissance and common attack types

📄 [Read Full Documentation](./SNORT.pdf)

---

### 3. 🔍 Suricata IDS/IPS
A high-performance, multi-threaded IDS/IPS engine configured for live traffic monitoring.
- Suricata installed on Ubuntu
- Configured with `suricata.yaml` and custom rule set
- Live log generation and tailing using `fast.log`
- Detection of ICMP, Nmap, and DNS anomalies

📄 [Read Full Documentation](./SURICATA.pdf)

---

### 4. 📊 ELK Stack (Local & Cloud)
Log management and analysis using ELK (Elasticsearch, Logstash, Kibana), with Zeek integration.
- Installed and configured on Linux (ELK Stack)
- Custom dashboards for system and network activity
- Zeek logs ingested into Kibana via Filebeat
- Second version hosted in cloud with ELK + Zeek visualization

📄 [Local ELK Setup](./ELK.pdf) | [Cloud ELK Setup](./ELK%202.0.pdf)

---

### 5. 🧠 Splunk + Windows Forwarding
Monitoring and alerting via Splunk with Windows Universal Forwarder integration.
- Splunk Enterprise installed on Linux
- Windows VM logs forwarded via Splunk Forwarder
- Simulated RDP brute-force attack using Hydra from Kali Linux
- Alert generation and index search for brute-force detection

📄 [Read Full Documentation](./SPLUNK.pdf)

---

## ⚙️ Skills & Tools Demonstrated

- 🔹 IDS/IPS: Snort, Suricata
- 🔹 SIEM & Logging: Splunk, ELK, Zeek, Filebeat
- 🔹 Virtualization & Networking: pfSense, VirtualBox, NAT/Internal Networking
- 🔹 Detection & Response: Brute-force simulation, Nmap scans, packet analysis
- 🔹 Log Analysis: Event correlation, alerting rules, dashboards

## 🧠 Why This Matters
These projects demonstrate my capability to simulate real-world enterprise environments, deploy security infrastructure, detect threats, and analyze logs using industry-standard tools. Built for both learning and showcasing my readiness for a cybersecurity role.

---

## 📫 Contact
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/gopal-rajguru2004/)  
Open to opportunities in SOC analysis, threat detection, or blue team cybersecurity roles.

