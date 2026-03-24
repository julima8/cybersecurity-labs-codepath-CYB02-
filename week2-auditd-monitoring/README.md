# Week 2 – Endpoint Monitoring (auditd)

## Lab: Host Intrusion Detection with auditd

### Objective
Monitor system activity and detect unauthorized file access or modifications using a Host Intrusion Detection System (HIDS).

### Tools Used
- auditd (Linux Audit Daemon)
- Linux CLI
- Vim

### What I Did
- Installed and configured auditd on a Linux virtual machine  
- Created and monitored files to simulate system activity  
- Wrote custom audit rules to track file modifications  
- Analyzed logs in `/var/log` to identify suspicious behavior  
- Used Vim to edit configuration and rule files  

---

## Project: System Monitoring & File Integrity

### Objective
Identify which system file was tampered with and analyze suspicious activity through audit logs.

### What I Did
- Investigated audit logs to detect unauthorized file changes  
- Tracked system calls and file access events  
- Identified indicators of suspicious behavior in system activity  
- Applied log analysis techniques to determine potential compromise  

---

## Key Concepts
- Host Intrusion Detection Systems (HIDS)  
- File integrity monitoring  
- System call tracking  
- Log analysis (Linux)  
- Endpoint security  

## Key Learning
This lab helped me understand how endpoint monitoring works in practice and how security teams detect unauthorized changes on systems using audit logs and rule-based monitoring.
