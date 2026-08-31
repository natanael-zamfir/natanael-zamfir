# ⚡️Nathan (Natanael) Zamfir: Cybersecurity Portfolio 🛡️

Entry-level cybersecurity professional with an engineering background and hands-on experience in threat hunting,
incident investigation, and defensive security. Skilled in analysing endpoint telemetry using Microsoft
Sentinel and Defender for Endpoint to investigate attacks and reconstruct attacker activity. Experienced
in ransomware investigations, Windows security hardening (DISA STIG), and practical blue team
operations across Windows and Linux environments.

> **Key Skills:** Threat Hunting | Incident Response | SIEM Monitoring | EDR Investigation | Vulnerability Management

### 🚨Threat Hunting and Security Operations

- **[🚨Threat Hunting Competition: Azuki Dead in The Water 🌊](https://github.com/natanael-zamfir/threat-hunt-azuki-d-in-the-water)**
> In this threat hunt competition, I conducted an end-to-end threat hunt and incident response investigation, reconstructing a ransomware attack through endpoint telemetry analysis and incident investigation.

- **[🚨Threat Hunting Scenario: Unauthorised Tor Browser Usage Detection 🧅](https://github.com/natanael-zamfir/threat-hunt-lab-tor-browser)**
> In this threat hunt scenario, I performed a threat hunt to identify unauthorised TOR browser usage, attributing activity to a specific user and device through endpoint and network evidence.
 
### 🛡️ Vulnerability Management Projects

- **[🖥️ Enterprise Vulnerability Management Program (End-to-End Lab)](https://github.com/natanael-zamfir/enterprise-vulnerability-management-program-end-to-end-lab/tree/main)**
> In this project, I simulate the implementation of a comprehensive vulnerability management program, from inception to completion.

### 🔬 Detection Engineering, Incident Response & Offensive Security

- **[🛡️ Detection Engineering & IR: SSH Brute-Force & Post-Exploitation in AWS ☁️](https://github.com/natanael-zamfir/wazuh-detection-engineering-aws-lab)**
> In this project **I built my own cloud detection lab**, I deployed a three-node Wazuh SIEM/XDR environment in my own AWS account (eu-west-2), brute-forced SSH with Hydra and `rockyou.txt`, and engineered custom correlation rules that escalate to critical only when a successful login follows a burst of failures from the same IP, then added File Integrity Monitoring rules that caught backdoor SSH keys, cron persistence and dropped payloads in real time.

- **[🛡️ SOC Incident Response: Host Triage & Data Exfiltration Investigation](https://github.com/natanael-zamfir/soc-incident-response-remediation)**
> In this two-part incident response exercise, I manually executed a host triage playbook on a Windows workstation with the SOAR offline, then investigated, contained and verified the eradication of an active data-exfiltration channel leaking customer PII over a non-standard port. *(CompTIA CertMaster Labs).*

- **[🔬 Digital Forensics: Disk Image Analysis, File Recovery & Key Recovery](https://github.com/natanael-zamfir/digital-forensics-disk-carving)**
> In this digital forensics investigation, I recovered evidence from raw disk images by uncovering a hidden logical partition, undeleting NTFS files with The Sleuth Kit, rebuilding a corrupted FAT16 boot sector in TestDisk to carve out lost files, and running the Windows EFS Data Recovery Agent lifecycle. *(CompTIA CertMaster Labs).*

- **[🕵️‍♂️ Root Cause Analysis: Insider Threat & Credential Harvesting](https://github.com/natanael-zamfir/insider-threat-root-cause-analysis)**
> In this root cause analysis, I correlated Wazuh alerts, Windows event logs, OPNsense firewall traffic, physical badge logs and a packet capture to attribute a domain controller audit-logging change to the real actor, rather than the admin account the SIEM alert blamed. *(CompTIA CertMaster Labs).*

- **[🎯 Web Application Penetration Testing & Adversary Emulation](https://github.com/natanael-zamfir/web-app-pentesting-adversary-emulation)**
> In this web application penetration test, I worked the gaining-access phase against DVWA using directory traversal, command injection and an unrestricted file upload to land a Meterpreter web shell, then ran an Adversary-in-the-Middle proxy interception and a reverse shell, mapping each step to MITRE ATT&CK for the defensive view. *(CompTIA CertMaster Labs).*

### 🔐 Windows 11 STIG Hardening (DISA)

- **[🖥️ Windows 11 STIG Hardening Implementations 🔐(v2r5) + MITRE ATT&CK Mapping](http://github.com/natanael-zamfir/stigs-windows-11-implementation)**

<details>
<summary>🖥️ View Windows 11 STIG Hardening Implementations 🔐</summary>

> 🛡️ **[WN11-CC-000070 – Virtualization-based Security must be enabled](https://github.com/natanael-zamfir/stigs-windows-11-implementation/blob/main/WN11-CC-000070%20%E2%80%93%20Virtualization-based%20Security%20must%20be%20enabled.md)**  
> I enabled virtualization-based security to isolate sensitive system components from memory and kernel attacks.
>
> 🛡️ **[WN11-CC-000075 – Credential Guard must be running (Domain-joined systems)](https://github.com/natanael-zamfir/stigs-windows-11-implementation/blob/main/WN11-CC-000075.md)**  
> I configured Credential Guard policies to protect login credentials in isolated memory (not applicable on this standalone system).
>
> 🛡️ **[WN11-CC-000326 – PowerShell Script Block Logging must be enabled](https://github.com/natanael-zamfir/stigs-windows-11-implementation/blob/main/WN11-CC-000326%20%E2%80%93%20PowerShell%20Script%20Block%20Logging%20must%20be%20enabled.md)**  
> I enabled script block logging so PowerShell commands and scripts executed on the system are fully recorded for investigation.
>
> 🛡️ **[WN11-CC-000327 – PowerShell Transcription must be enabled on Windows 11](https://github.com/natanael-zamfir/stigs-windows-11-implementation/blob/main/WN11-CC-000327%20%E2%80%93%20PowerShell%20Transcription%20must%20be%20enabled%20on%20Windows%2011.md)**  
> I enabled PowerShell transcription to create readable session logs that help reconstruct attacker activity.
>
> 🛡️ **[WN11-CC-000066 – Command line data must be included in process creation events](https://github.com/natanael-zamfir/stigs-windows-11-implementation/blob/main/WN11-CC-000066%20%E2%80%93%20Command%20line%20data%20must%20be%20included%20in%20process%20creation%20events.md)**  
> I configured Windows to log full command-line arguments so executed processes can be clearly investigated.
>
> 🛡️ **[WN11-AU-000030 – Audit Security Group Management must be enabled (Success)](https://github.com/natanael-zamfir/stigs-windows-11-implementation/blob/main/WN11-AU-000030%20%E2%80%93%20Audit%20Security%20Group%20Management%20must%20be%20enabled.md)**  
> I enabled auditing of security group changes so privilege and permission modifications are tracked.
>
> 🛡️ **[WN11-SO-000205 – LanMan authentication level must be NTLMv2 only](https://github.com/natanael-zamfir/stigs-windows-11-implementation/blob/main/WN11-SO-000205%20%E2%80%93%20LanMan%20authentication%20level%20must%20be%20NTLMv2%20only.md)**  
> I enforced NTLMv2-only authentication to block weak legacy authentication protocols.
>
> 🛡️ **[WN11-CC-000038 – WDigest Authentication must be disabled](https://github.com/natanael-zamfir/stigs-windows-11-implementation/blob/main/WN11-CC-000038%20%E2%80%93%20WDigest%20Authentication%20must%20be%20disabled.md)**  
> I disabled WDigest so passwords are not stored in memory where attackers could extract them.
>
> 🛡️ **[WN11-CC-000210 – Microsoft Defender SmartScreen for Explorer must be enabled](https://github.com/natanael-zamfir/stigs-windows-11-implementation/blob/main/WN11-CC-000210%20%E2%80%93%20The%20Microsoft%20Defender%20SmartScreen%20for%20Explorer%20must%20be%20enabled.md)**  
> I enabled SmartScreen to block or warn against running suspicious downloaded files.
>
> 🛡️ **[WN11-CC-000155 – Solicited Remote Assistance must not be allowed](https://github.com/natanael-zamfir/stigs-windows-11-implementation/blob/main/WN11-CC-000155%20%E2%80%93%20Solicited%20Remote%20Assistance%20must%20not%20be%20allowed.md)**  
> I disabled Solicited Remote Assistance to prevent users from granting remote control to attackers through scams.
>
> <img width="1832" height="728" alt="image" src="https://github.com/user-attachments/assets/4a63bceb-f1eb-4e2c-9a1b-d0e4310beab9" />

</details>


---
<h2>🧰 Technologies & Tools</h2>

### Cloud Platforms
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Azure-0078D4?&style=for-the-badge&logo=microsoftazure&logoColor=white" />
    <img src="https://img.shields.io/badge/-Amazon_Web_Services-FF9900?&style=for-the-badge&logo=amazonwebservices&logoColor=white" />
</div>

### SIEM, Detection & EDR
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Sentinel-00A4EF?&style=for-the-badge&logo=microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Microsoft_Defender_for_Endpoint-00A4EF?&style=for-the-badge&logo=microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Wazuh_SIEM_%2F_XDR-00A4EF?&style=for-the-badge&logo=wazuh&logoColor=white" />
    <img src="https://img.shields.io/badge/-Security_Onion-43B02A?&style=for-the-badge&logo=linux&logoColor=white" />
    <img src="https://img.shields.io/badge/-File_Integrity_Monitoring-2E7D32?&style=for-the-badge&logo=gnubash&logoColor=white" />
</div>

### Network & Traffic Analysis
<div>
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=wireshark&logoColor=white" />
    <img src="https://img.shields.io/badge/-OPNsense_Firewall-D94A38?&style=for-the-badge&logo=opnsense&logoColor=white" />
</div>

### Offensive & Testing
<div>
    <img src="https://img.shields.io/badge/-Hydra-D32F2F?&style=for-the-badge&logo=hackaday&logoColor=white" />
    <img src="https://img.shields.io/badge/-Metasploit_Framework-1E88E5?&style=for-the-badge&logo=rapid7&logoColor=white" />
    <img src="https://img.shields.io/badge/-MSFvenom-005571?&style=for-the-badge&logo=hackthebox&logoColor=white" />
    <img src="https://img.shields.io/badge/-Burp_Suite-FF6633?&style=for-the-badge&logo=burpsuite&logoColor=white" />
    <img src="https://img.shields.io/badge/-Social--Engineer_Toolkit_(SET)-333333?&style=for-the-badge&logo=kalilinux&logoColor=white" />
</div>

### Forensics & Host Tools
<div>
    <img src="https://img.shields.io/badge/-The_Sleuth_Kit_(TSK)-333333?&style=for-the-badge&logo=linux&logoColor=white" />
    <img src="https://img.shields.io/badge/-TestDisk-4A154B?&style=for-the-badge&logo=slack&logoColor=white" />
    <img src="https://img.shields.io/badge/-Fiwalk-1E88E5?&style=for-the-badge&logo=target&logoColor=white" />
    <img src="https://img.shields.io/badge/-Sysinternals-0078D6?&style=for-the-badge&logo=windows&logoColor=white" />
    <img src="https://img.shields.io/badge/-WinSCP-4A90E2?&style=for-the-badge&logo=winscp&logoColor=white" />
    <img src="https://img.shields.io/badge/-Windows_EFS-0078D6?&style=for-the-badge&logo=windows&logoColor=white" />
</div>

### Systems & Infrastructure
<div>
    <img src="https://img.shields.io/badge/-Ubuntu_Linux-E95420?&style=for-the-badge&logo=ubuntu&logoColor=white" />
    <img src="https://img.shields.io/badge/-Kali_Linux-557C94?&style=for-the-badge&logo=kalilinux&logoColor=white" />
    <img src="https://img.shields.io/badge/-Windows_Server_2019-0078D6?&style=for-the-badge&logo=windows&logoColor=white" />
    <img src="https://img.shields.io/badge/-Apache_HTTP_Server-D22128?&style=for-the-badge&logo=apache&logoColor=white" />
</div>

### Vulnerability Management
<div>
    <img src="https://img.shields.io/badge/-Tenable-3E4D88?&style=for-the-badge&logo=tenable&logoColor=white" />
</div>

### Threat Hunting & Querying
<div>
    <img src="https://img.shields.io/badge/-KQL_(Kusto_Query_Language)-005571?&style=for-the-badge&logo=microsoft&logoColor=white" />
</div>

### Scripting & Automation
<div>
    <img src="https://img.shields.io/badge/-Python-3776AB?&style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/-PowerShell-5391FE?&style=for-the-badge&logo=powershell&logoColor=white" />
</div>

### Data Analysis
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Excel-217346?&style=for-the-badge&logo=microsoftexcel&logoColor=white" />
    <img src="https://img.shields.io/badge/-Google_Apps_Script-4285F4?&style=for-the-badge&logo=google&logoColor=white" />
</div>

---

<h2>🛡️ Security Concepts</h2>

### Detection & Threat Hunting
<div>
  <img src="https://img.shields.io/badge/-Detection_Engineering-6A1B9A?style=for-the-badge&logo=target&logoColor=white" />
  <img src="https://img.shields.io/badge/-Threat_Hunting-6A1B9A?style=for-the-badge&logo=datadog&logoColor=white" />
  <img src="https://img.shields.io/badge/-Custom_Rule_Correlation-1565C0?style=for-the-badge&logo=splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/-SIEM_Log_Correlation-1565C0?style=for-the-badge&logo=splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/-File_Integrity_Monitoring_(FIM)-00838F?style=for-the-badge&logo=checkmarx&logoColor=white" />
  <img src="https://img.shields.io/badge/-Brute--Force_Analysis-D32F2F?style=for-the-badge&logo=security&logoColor=white" />
  <img src="https://img.shields.io/badge/-Endpoint_Detection_%26_Response-1E88E5?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/-MITRE_ATT%26CK_Mapping-FF6F00?style=for-the-badge&logo=mitre&logoColor=white" />
</div>

### Incident Response & Investigation
<div>
  <img src="https://img.shields.io/badge/-Incident_Response-AE0000?style=for-the-badge&logo=security&logoColor=white" />
  <img src="https://img.shields.io/badge/-Incident_Response_Playbooks-AE0000?style=for-the-badge&logo=security&logoColor=white" />
  <img src="https://img.shields.io/badge/-Root_Cause_Analysis-8E24AA?style=for-the-badge&logo=target&logoColor=white" />
  <img src="https://img.shields.io/badge/-Ransomware_Analysis-8B0000?style=for-the-badge&logo=hackaday&logoColor=white" />
  <img src="https://img.shields.io/badge/-Insider_Threat_Detection-D32F2F?style=for-the-badge&logo=hackaday&logoColor=white" />
  <img src="https://img.shields.io/badge/-Process_Triage-1565C0?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/-Windows_Event_Log_Analysis-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/-Post--Incident_Validation-00838F?style=for-the-badge&logo=checkmarx&logoColor=white" />
</div>

### Network & Exfiltration
<div>
  <img src="https://img.shields.io/badge/-Network_Traffic_Analysis-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/-Deep_Packet_Inspection-00897B?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/-Data_Exfiltration_Triage-C62828?style=for-the-badge&logo=hackaday&logoColor=white" />
  <img src="https://img.shields.io/badge/-Adversary--in--the--Middle_(AitM)-E65100?style=for-the-badge&logo=cloudflare&logoColor=white" />
</div>

### Offensive Techniques
<div>
  <img src="https://img.shields.io/badge/-Penetration_Testing-D32F2F?style=for-the-badge&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/-Command_Injection-E65100?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/-Directory_Traversal-7B1FA2?style=for-the-badge&logo=apache&logoColor=white" />
  <img src="https://img.shields.io/badge/-Web_Shell_Deployment-2E7D32?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/-Reverse_TCP_Egress-1565C0?style=for-the-badge&logo=cisco&logoColor=white" />
</div>

### Attacker Behaviour & Persistence
<div>
  <img src="https://img.shields.io/badge/-Lateral_Movement_Detection-5D4037?style=for-the-badge&logo=probot&logoColor=white" />
  <img src="https://img.shields.io/badge/-Persistence_Detection-283593?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/-Anti--Forensics_Analysis-37474F?style=for-the-badge&logo=ghost&logoColor=white" />
  <img src="https://img.shields.io/badge/-Timeline_Reconstruction-2E7D32?style=for-the-badge&logo=clockify&logoColor=white" />
</div>

### Digital Forensics & Recovery
<div>
  <img src="https://img.shields.io/badge/-Digital_Forensics-455A64?style=for-the-badge&logo=forensic-science&logoColor=white" />
  <img src="https://img.shields.io/badge/-Disk_Forensics-2E7D32?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/-File_Carving-E65100?style=for-the-badge&logo=adguard&logoColor=white" />
  <img src="https://img.shields.io/badge/-MBR_%2F_Partition_Analysis-00838F?style=for-the-badge&logo=serverfault&logoColor=white" />
  <img src="https://img.shields.io/badge/-NTFS_Undelete-C2185B?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/-Boot_Sector_Rebuild-5D4037?style=for-the-badge&logo=apache&logoColor=white" />
  <img src="https://img.shields.io/badge/-Cryptographic_Key_Recovery-1565C0?style=for-the-badge&logo=letsencrypt&logoColor=white" />
</div>

### Evidence Handling & Hardening
<div>
  <img src="https://img.shields.io/badge/-Evidence_Handling_%26_Quarantine-455A64?style=for-the-badge&logo=box&logoColor=white" />
  <img src="https://img.shields.io/badge/-SHA--256_File_Hashing-2E7D32?style=for-the-badge&logo=gnuprivacyguard&logoColor=white" />
  <img src="https://img.shields.io/badge/-Security_Hardening-546E7A?style=for-the-badge&logo=shield&logoColor=white" />
</div>

### Compliance & Security Standards
<div>
  <img src="https://img.shields.io/badge/-DISA_STIG_Implementation-2E7D32?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/-Security_Baseline_Configuration-1565C0?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/-System_Hardening_Standards-6A1B9A?style=for-the-badge&logo=databricks&logoColor=white" />
</div>
