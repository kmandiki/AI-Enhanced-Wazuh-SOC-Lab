#  AI-Enhanced Wazuh SOC Lab

##  Project Overview

This repository documents the deployment, troubleshooting, and enhancement of a home Security Operations 
Center(SOC) lab.

#### Lab Architecture
                    AI-Enhanced Wazuh SOC Lab

                           GREEN NETWORK
                   ───────────────────────────

      ┌──────────────┐                 ┌─────────────────┐
      │   AD-DC01    │                 │  Ubuntu-SOC-2   │
      ├──────────────┤                 ├─────────────────┤
      │ Active Dir   │                 │ Wazuh Manager   │
      │ DNS          │                 │ Wazuh Dashboard │
      │ DHCP         │                 │ Wazuh Indexer   │
      │ 10.0.10.10   │                 │ Ollama          │
      └──────┬───────┘                 │ Open WebUI      │
             │                         │ 10.0.10.20      │
             │                         └────────┬────────┘
             │                                  │
             ▼                                  ▼

                    ┌─────────────────┐
                    │      WIN10      │
                    ├─────────────────┤
                    │ Sysmon          │
                    │ Wazuh Agent     │
                    │ Browser Access  │
                    └─────────────────┘

                    Open WebUI Access
                 http://10.0.10.20:3000
##  Objectives

  -  Deploy a functional SIEM platform
  -  Monitor Windows endpoint activity
  -  Collect Sysmon telemetry
  -  Integrate Active Directory services
  -  Add a local AI assistant for log analysis
    
###  Technologies Used
  -  VirtualBox
  -  Ubuntu Server
  -  Windows 10
  -  Active Directory
  -  Wazuh
  -  Sysmon
  -  Docker
  -  Ollama
  -  Open WebUI
    

###  Current Status
  - ✅ Active Directory Operational
  - ✅ Wazuh Operational
  - ✅ Sysmon Operational
  - ✅ Ollama Operational
  - ✅ Open WebUI Operational
  - ✅AI Model Integration Operational

###  Skills Demonstrated
  -  Linux Administration
  -  VirtualBox Administration
  -  LVM Storage Expansion
  -  Wazuh Deployment
  -  Sysmon Integration
  -  Docker Management
  -  Network Troubleshooting
  -  AI Integration
  -  Incident Troubleshooting

###  Future Improvements
  -  Atomic Red Team Testing
  -  Detection Engineering
  -  Sigma Rules
  -  MITRE ATT&CK Mapping
  -  Malware Analysis Workflows
  -  AI-Assisted Alert Triage

###  Key Achievements
  -  Recovered Wazuh after storage exhaustion
  -  Expanded Ubuntu storage from 29GB to 58GB
  -  Extended Linux LVM volumes
  -  Integrated Sysmon telementry
  -  Installed Ollama
  -  Deployed Open WebUI
  -  Connected AI models to Open WebUI
  -  Built an AI-assisted SOC environment

###  Author

Killian Mandiki

Cybersecurity Home Lab Project

