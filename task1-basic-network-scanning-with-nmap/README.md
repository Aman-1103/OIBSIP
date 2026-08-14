# OBISIP
---
## CyberSecurity Project
---
**Submitted by :** AMAN DAHIWALE

**Organization:** OASIS INFOBYTE

**Date:** AUGUST 2026

---
## 1.Basic Network Scanning with Nmap

**Objective:** Perform a network scan to identify open ports and services running on a local machine or virtual machine using Nmap, and document your findings with security analysis



---
## 2. Environment/Tools Used

**Operating system:** Kali Linux

**Tool Used:** Nmap(Network Mapper)v7.95

**Interface:** terminal(zsh Shell)

**Target Network:** `152.59.30.157`

---

## 3.Step-by-Step Procedure**

### - Step 1: Installing a Virtual Machine and Kali Linux

First, install **VirtualBox** or **VMware** on your system. Create a new virtual machine and allocate the required RAM, CPU, and storage. Download the **Kali Linux ISO** and attach it to the virtual machine. Start the VM and follow the Kali Linux installation steps to configure the system. After installation, restart the VM and boot into Kali Linux.

### -Step 2: Running the Nmap Scan

Open the Kali Linux terminal and run the **Nmap** command on the local host IP address as required by the project task. This will scan the target and display the requested network information.

---
## 4.COMMANDS:
-Basic Nmap scan:`nmap 10.0.2.15 `

-Service version scan: `nmap 10.0.2.15`

-OS Detection scan:`nmap 10.0.2.15`

---
### ScreenShot of the Program:


<img width="800" height="600" alt="Screenshot_2026-08-14_23_10_23" src="https://github.com/user-attachments/assets/fec35955-2241-42d5-9fba-c6b78970cf72" />

---
### 1.What Nmap is?
=*Nmap (Network Mapper) is an open-source tool used to scan networks and identify devices, open ports, running services, and other network information. It is commonly used by network administrators and security professionals for network management and security testing.*

### 2.Why network scanning matters ?
=*Network scanning matters because it helps identify connected devices, open ports, active services, and potential security weaknesses. It allows organizations to monitor their networks, detect unauthorized devices, troubleshoot problems, and improve overall security.*

### 3.What are the ethical use Guidelines?  
=*Ethical use guidelines for Nmap include:*
 - *Scan only networks you own or have permission to test.*
 - *Respect privacy and confidentiality.*
 - *Avoid disrupting or damaging systems.*
 - *Use scans for legitimate security purposes.*
 - *Report discovered vulnerabilities responsibly.*

---

### 4. Conclusion
*This Nmap project provided practical experience in network scanning and basic cybersecurity reconnaissance. I installed Kali Linux and successfully used Nmap to perform different types of scans. The basic Nmap scan helped identify active hosts and open ports, while the `-sV` option provided information about the services and their versions running on those ports. I also explored the `-o` option to save scan results for further analysis and documentation. Overall, this project strengthened my understanding of network discovery, service enumeration, and security assessment. These skills are valuable for identifying potential vulnerabilities and supporting effective cybersecurity practices in real-world environments.*








