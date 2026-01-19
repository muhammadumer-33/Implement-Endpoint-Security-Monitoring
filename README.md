# 🛡️ Assignment 01 – Endpoint Security & Monitoring  
**Platform:** internee.pk  

**Name:** Muhammad Umer  

---

## 📌 Task Title  
**Implement Endpoint Security & Monitoring**

---

## 🎯 Objective  

The objective of this assignment is to install and configure **Wazuh SIEM** in a lab environment and enable **File Integrity Monitoring (FIM)** to detect unauthorized file and registry changes in real time.

This task establishes a strong foundation for **SOC operations**, **endpoint security**, and **security monitoring & analysis**.

---

## 🧪 Environment Details  

| Component | Details |
|---------|--------|
| **Wazuh Manager OS** | Ubuntu Linux |
| **Wazuh Version** | 4.12.0 |
| **Agent System** | Windows 10 |
| **Monitoring Feature** | File Integrity Monitoring (FIM) |

---

## 🔧 Task Implementation  

### 🔹 Step 1: Wazuh Manager Installation  

- Wazuh Manager was installed on **Ubuntu Linux**.
- After installation, the Wazuh services were verified using `systemctl`.
- All Wazuh components were confirmed to be running correctly.

✅ **Result:** Wazuh Manager installed and operational.

---

### 🔹 Step 2: Wazuh Agent Installation on Windows  

- The Wazuh Agent was installed on a **Windows system**.
- The agent was configured with:
  - Wazuh Manager IP address
  - Unique authentication key
- Agent status confirmed:
  - Service running
  - Successfully connected to the Wazuh Manager

✅ **Result:** Agent successfully enrolled and connected.

---

### 🔹 Step 3: Agent Configuration Verification  

- Agent configuration directory was inspected.
- Required binaries and configuration files were present.
- This confirms correct installation and operational status of the agent.

✅ **Result:** Agent installation verified.

---

### 🔹 Step 4: File Integrity Monitoring (FIM) Configuration  

- FIM was configured using the `ossec.conf` file.
- Monitoring enabled for:
  - Critical system directories
  - Startup folders
  - Windows registry keys
- **Real-time monitoring** was enabled to detect immediate changes.

✅ **Result:** FIM actively monitoring files and registry changes.

---

## 📊 Outcome & Monitoring  

- Unauthorized file changes are detected instantly.
- Registry modifications are logged in real time.
- Events are visible through the Wazuh Dashboard.
- Provides enhanced endpoint visibility and security monitoring.

---

## ✅ Conclusion  

Task 01 has been **successfully completed**.

- Wazuh Manager and Agent are properly installed.
- Secure communication between manager and agent is established.
- File Integrity Monitoring (FIM) is enabled and functioning correctly.
- The system provides **real-time security visibility** for critical files and registry entries.

This setup lays the groundwork for advanced **SOC monitoring**, **incident detection**, and **threat analysis**.

---

## 🚀 Author  

**Muhammad Umer**  
Cybersecurity Intern | SOC & SIEM Enthusiast  

---

## 🔐 Keywords  

`Wazuh` `SIEM` `Endpoint Security` `File Integrity Monitoring` `SOC` `Cybersecurity`  
