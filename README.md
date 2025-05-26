# 🔥 Palo Alto Firewall Configuration & Security Labs

## 📌 Project Overview
This project contains a full suite of hands-on labs simulating enterprise firewall deployment using Palo Alto Networks technology. Topics include system setup, security policies, high availability, packet inspection, encrypted traffic handling, and administrator role configuration. All labs were performed in a virtual training environment designed to mirror production-level scenarios.

> 🛡️ This repo showcases security-focused tasks ranging from Nmap network scanning to deep packet inspection and log analysis, with both GUI- and CLI-based workflows.

---

## 🛠 Tools & Technologies
- **Palo Alto NGFW (PAN-OS)**  
- **CLI & Web GUI Configurations**
- **Security & NAT Policies**
- **Decryption Policies (SSL Forward Proxy)**
- **High Availability (HA)**
- **Authentication via LDAP & RADIUS**
- **Packet Capture Tools & Log Filtering**
- **Nmap & Host Discovery Techniques**

---

## ⚙️ Key Labs & Topics

### 1. 🔧 Initial Setup & Management Access
- Connect to PAN Web GUI
- Configure DNS, NTP, banners, and management IPs
- Check for PAN-OS updates

🗂 Files:  
- `PAN10_EDU210_Lab_01-1.pdf`  
- `Configuring Palo Alto Firewall Basic Using CLI-1.docx`

---

### 2. 📁 Configuration Management & Logging
- Save/Load configuration snapshots
- Use the Preview/Revert functions
- Filter logs and perform search-based analysis

🗂 Files:  
- `PAN10_EDU210_Lab_02-1.pdf`  
- `1.5 Assignment Packet Capture and Analysis.docx`

---

### 3. 👥 Admin Account & Authentication Setup
- Create local, LDAP, and RADIUS authentication profiles
- Configure admin roles and authentication sequences

🗂 Files:  
- `PAN10_EDU210_Lab_03-1.pdf`

---

### 4. 🌐 Connecting the Firewall to Production Networks
- Configure Layer 3 interfaces and a virtual router
- Build and test multiple security zones

🗂 Files:  
- `PAN10_EDU210_Lab_04-1.pdf`

---

### 5. 🔐 Security Policy Creation
- Write and apply inbound/outbound rules
- Enforce application-specific and threat-based policies

🗂 Files:  
- `PAN10_EDU210_Lab_05-1.pdf`  
- `2.2 Activity Security Policies.docx`

---

### 6. 🌍 Threat Defense with External Dynamic Lists (EDLs)
- Block access by country (Geo-IP)
- Create anti-spyware, URL filtering, and vulnerability protection profiles

🗂 Files:  
- `PAN10_EDU210_Lab_07-1.pdf`

---

### 7. 🕵️ SSL Decryption & Inspection
- Deploy self-signed certificates
- Apply SSL decryption policies for outbound traffic
- Test and review decrypted logs

🗂 Files:  
- `PAN10_EDU210_Lab_13-1.pdf`

---

### 8. 🔁 High Availability (HA)
- Configure Active/Passive HA settings
- Monitor HA health and simulate failovers

🗂 Files:  
- `PAN9_EDU210_Lab_13-1.pdf`

---

### 9. 🌐 Network Scanning & Host Discovery
- Perform Nmap scans using various techniques: SYN, UDP, list scan, and port ranges
- Analyze scan results and detect filtered or open ports

🗂 Files:  
- `Performing a Network Scan-1-1.docx`

---

## 🧪 Learning Outcomes
- Built layered security policies with real-world tools
- Practiced critical firewall functions including NAT, HA, and log filtering
- Developed packet capture and analysis skills
- Learned to evaluate live traffic, inspect encrypted flows, and detect anomalies
- Simulated multi-admin role access and centralized authentication

---

## 📂 Repository Structure
palo-alto-firewall-labs/
├── README.md
├── Lab-PDFs/
│   ├── PAN10_EDU210_Lab_01-1.pdf
│   ├── ...
├── Policies/
│   └── 2.2 Activity Security Policies.docx
├── CLI-Commands/
│   └── Configuring Palo Alto Firewall Basic Using CLI-1.docx
├── Analysis/
│   ├── Performing a Network Scan-1-1.docx
│   └── Packet Capture Assignment.docx

---

## 👤 Authors
> Group Project — ECPI University, CYB430  
All work performed in an academic simulation environment.  

---

## ✅ License
This repository is for educational and demonstration purposes only. No proprietary or confidential systems were accessed or tested.

