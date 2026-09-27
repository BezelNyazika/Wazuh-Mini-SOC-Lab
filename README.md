# Wazuh Mini SOC Lab

Hands-on SOC home lab using Wazuh, Windows Server, Sysmon and an isolated VirtualBox network.

## Architecture
- Ubuntu: Wazuh Manager, Indexer and Dashboard — 192.168.50.10
- Windows Server DC01: Wazuh Agent — 192.168.50.20
- Kali: planned security-testing endpoint — 192.168.50.30
- Windows 11: planned endpoint — 192.168.50.40

## Goals
- Endpoint monitoring and Windows log collection
- Sysmon telemetry
- File Integrity Monitoring and SCA
- Detection scenarios and MITRE ATT&CK mapping
- Controlled testing and recruiter-facing documentation

## Status
- [x] Central Wazuh components deployed
- [x] SOC-Lab network configured
- [x] Windows Server VM created
- [x] Connectivity tested
- [ ] Agent enrollment
- [ ] Sysmon validation
- [ ] Detection scenarios
- [ ] Portfolio screenshots
