# Detection Lab 1.0

**Status:** Work in Progress  
**Author:** Steven Loucks  
**Version:** 1.0  
**Lab Type:** Standalone Detection Environment (Post-AD Lab Progression)  
**Focus:** Threat Detection, Logging, EDR, IDS, and MITRE ATT&CK Mapping

---

## Overview

Detection Lab 1.0 builds directly on the foundation established in [Active Directory Lab 1.0](https://github.com/sloucks623/lab-active-directory-1.0). While the AD lab focused on infrastructure, domain services, and internal networking, this lab shifts to **detecting, analyzing, and responding to threats** using modern security tooling.

---

## Objectives

- Deploy and configure open-source EDR/IDS tools
- Capture and analyze malicious behavior in a Windows domain
- Map detections to MITRE ATT&CK
- Generate and visualize logs from real-world simulation tools
- Practice detection engineering and incident response basics

---

## Tools Planned

| Tool Type | Tool Name(s) | Purpose |
|-----------|--------------|---------|
| EDR       | Velociraptor, Sysmon + Sigma | Endpoint telemetry & DFIR |
| IDS       | Zeek, Suricata | Network-based threat detection |
| Logging   | Elastic Stack (ELK), Graylog | Log aggregation & visualization |
| Testing   | Atomic Red Team | Safe attack simulation |

---

## Topology

### Source Architecture (From AD Lab 1.0)
> ![AD Lab 1.0 Topology](### Source Architecture (From AD Lab 1.0)
![AD Lab 1.0 Topology](https://raw.githubusercontent.com/sloucks623/lab-active-directory-1.0/main/diagrams/ad-lab1.0.drawio.png)  
*Original lab topology this detection environment builds upon.*)  
*Original lab topology this detection environment builds upon.*

### Detection Lab 1.0 – Planned Logical Diagram
> _**[Diagram in progress: `diagram/detection-lab1-topology.drawio.png`]**_  
_A detailed detection-focused layout will be uploaded once finalized in Draw.io._

---

## Installation Notes

_(Coming soon: Step-by-step installation walkthroughs for each tool)_

---

## Use Cases and Simulated Scenarios

- Detecting malicious PowerShell with Sysmon
- Identifying beaconing traffic with Zeek
- Parsing logs to uncover persistence techniques
- Elastic visualizations of MITRE technique coverage

---

## MITRE ATT&CK Coverage

| Tactic      | Technique Example     | Tool Used         |
|-------------|------------------------|-------------------|
| Execution   | T1059.001 PowerShell   | Sysmon, Sigma     |
| Discovery   | T1082 System Info      | Velociraptor      |
| Command & Control | T1071.001 Web Traffic | Zeek         |

---

## Screenshots

_(Screenshots of detections and dashboards will be added here.)_

---

## Author Notes

This project is part of my cybersecurity training and portfolio development. All tools used are open-source and installed in a local virtual lab for educational purposes.
