# SOC Detection Queries 🔍

This repository contains a collection of detection queries written in various query languages used in SOC environments, such as:

- **KQL** (Kusto Query Language) for Microsoft Sentinel
- **SPL** (Search Processing Language) for Splunk
- **Sigma Rules** for generic rule-to-SIEM conversion

Each query is aimed at identifying specific tactics or techniques from the [MITRE ATT&CK](https://attack.mitre.org/) framework.

---

## 📁 Directory Structure

| Folder           | Description                              |
|------------------|------------------------------------------|
| sentinel-kql     | KQL queries for Microsoft Sentinel        |
| splunk-spl       | SPL queries for Splunk                   |
| sigma-rules      | Sigma rules in YAML format               |

---

## 🔒 MITRE ATT&CK Mapping Examples

| Query Name                       | ATT&CK Technique                     |
|----------------------------------|--------------------------------------|
| brute_force_login.kql           | T1110 - Brute Force                  |
| powershell_obfuscation.kql      | T1059.001 - PowerShell               |
| dns_tunneling.spl               | T1071.004 - Application Layer Protocol |
