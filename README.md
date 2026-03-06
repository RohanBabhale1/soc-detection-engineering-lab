# 🛡️ SOC Investigation & Detection Engineering Lab

## Overview
A full cyber attack lifecycle simulation and detection project using Splunk SIEM,
Kali Linux, and Metasploitable2 in an isolated virtual lab environment.

## Attack Phases
- Reconnaissance (Nmap)
- Exploitation (Metasploit - vsftpd 2.3.4 backdoor)
- Reverse Shell (Netcat)
- Post-Exploitation (privilege escalation, data exfil simulation)

## Detection Engineering
- Port scan detection (SPL)
- Brute force detection (SPL)
- Reverse shell traffic detection (SPL)
- Suspicious outbound connection alerts

## MITRE ATT&CK Techniques Mapped
T1046, T1190, T1059, T1071, T1105, T1087

## Tools Used
Splunk | Kali Linux | Metasploitable2 | Nmap | Metasploit | Netcat | Wireshark

