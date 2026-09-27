# Architecture

The lab uses an isolated VirtualBox Internal Network named SOC-Lab.

- Ubuntu Wazuh server: 192.168.50.10/24
- Windows Server DC01: 192.168.50.20/24
- Kali Linux: 192.168.50.30/24 planned
- Windows 11: 192.168.50.40/24 planned

## Data Flow

Windows Server -> Wazuh Agent -> Wazuh Manager -> Wazuh Indexer -> Wazuh Dashboard

Sysmon -> Windows Event Log -> Wazuh Agent -> Wazuh Manager

## Core Ports

- TCP 1514 — agent communication
- TCP 1515 — agent enrollment
- TCP 55000 — Wazuh API
- TCP 443 — Dashboard
