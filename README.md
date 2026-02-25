# ⚡️ Natanael Zamfir: Cybersecurity Project Portfolio 🛡️

Cybersecurity Analyst with an engineering background and hands-on experience in threat hunting,
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

### Cloud Platform
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Azure-0078D4?&style=for-the-badge&logo=microsoftazure&logoColor=white" />
</div>

### SIEM, Detection & EDR
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Sentinel-00A4EF?&style=for-the-badge&logo=microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Microsoft_Defender_for_Endpoint-00A4EF?&style=for-the-badge&logo=microsoft&logoColor=white" />
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

### Security Concepts
<div>
  <img src="https://img.shields.io/badge/-Threat_Hunting-6A1B9A?style=for-the-badge&logo=datadog&logoColor=white" />
  <img src="https://img.shields.io/badge/-Incident_Response-AE0000?style=for-the-badge&logo=security&logoColor=white" />
  <img src="https://img.shields.io/badge/-Ransomware_Analysis-8B0000?style=for-the-badge&logo=hackaday&logoColor=white" />
  <img src="https://img.shields.io/badge/-Digital_Forensics-455A64?style=for-the-badge&logo=forensic-science&logoColor=white" />
  <img src="https://img.shields.io/badge/-Endpoint_Detection_%26_Response-1E88E5?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/-MITRE_ATT%26CK_Mapping-FF6F00?style=for-the-badge&logo=mitre&logoColor=white" />
  <img src="https://img.shields.io/badge/-Lateral_Movement_Detection-5D4037?style=for-the-badge&logo=probot&logoColor=white" />
  <img src="https://img.shields.io/badge/-Persistence_Detection-283593?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/-Anti--Forensics_Analysis-37474F?style=for-the-badge&logo=ghost&logoColor=white" />
  <img src="https://img.shields.io/badge/-Timeline_Reconstruction-2E7D32?style=for-the-badge&logo=clockify&logoColor=white" />
  <img src="https://img.shields.io/badge/-Security_Hardening-546E7A?style=for-the-badge&logo=shield&logoColor=white" />
</div>

### Compliance & Security Standards
<div>
  <img src="https://img.shields.io/badge/-DISA_STIG_Implementation-2E7D32?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/-Security_Baseline_Configuration-1565C0?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/-System_Hardening_Standards-6A1B9A?style=for-the-badge&logo=databricks&logoColor=white" />
</div>

### Data Analysis
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Excel-217346?&style=for-the-badge&logo=microsoftexcel&logoColor=white" />
    <img src="https://img.shields.io/badge/-Google_Apps_Script-4285F4?&style=for-the-badge&logo=google&logoColor=white" />
</div>




