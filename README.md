# 🛡️ Endpoint Security & Firewall Troubleshooting Lab (VMware)

---

## 📌 Overview  
Built a hands-on endpoint security lab to simulate real-world IT help desk and security scenarios. This project focuses on configuring firewall rules, performing antivirus scans, and analyzing system logs to diagnose and resolve connectivity and authentication issues.

---

## 🛠️ Technologies Used  
- Windows Security  
- Windows Defender Firewall with Advanced Security  
- Event Viewer  
- Remote Desktop Protocol (RDP)  
- VMware Workstation  

---

## 🧱 Lab Architecture  
- Windows 10/11 virtual machine acting as endpoint  
- Firewall rules configured locally on endpoint  
- Remote access via RDP from host machine  
- Event logs monitored for authentication activity  

---

## ⚙️ Setup Summary  

### 🔹 Endpoint Configuration  
- Configured Windows Security settings  
- Verified system protection status  
- Performed antivirus scans (Quick & Full)  

### 🔹 Firewall Configuration  
- Accessed Windows Defender Firewall (Advanced Settings)  
- Created inbound rule blocking TCP port 3389 (RDP)  
- Validated rule impact on remote connectivity  

### 🔹 Remote Access (RDP)  
- Enabled Remote Desktop on VM  
- Successfully established remote connection  
- Simulated connection failure via firewall rule  

### 🔹 Log Analysis  
- Used Event Viewer to analyze security logs  
- Reviewed:
  - Event ID 4624 (successful login)  
  - Event ID 4625 (failed login)  
- Correlated login attempts with system activity  

---

## 🧪 Troubleshooting Scenario  

**Issue:**  
User unable to connect via Remote Desktop  

**Steps Taken:**  
- Verified RDP was enabled  
- Checked IP address and network connectivity  
- Reviewed firewall rules  
- Identified blocked port 3389  
- Modified firewall rule to restore access  

**Resolution:**  
Re-enabled RDP connectivity by correcting firewall configuration  

---

## 📊 Key Findings  
- Firewall misconfigurations can block critical services like RDP  
- Port 3389 is required for remote desktop access  
- Event Viewer provides insight into authentication activity  
- Endpoint security tools are essential for monitoring and protection  

---

## 🧠 Skills Demonstrated  
- Endpoint security configuration  
- Firewall rule management  
- Remote access troubleshooting  
- Log analysis and monitoring  
- Structured problem-solving  
