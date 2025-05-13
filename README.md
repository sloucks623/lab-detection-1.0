# Detection Lab 1.0

**Status:** Work in Progress  
**Author:** Steven Loucks  
**Version:** 1.0  
**Lab Type:** Standalone Detection Environment  
**Focus:** Threat Detection, Logging, EDR, IDS, and MITRE ATT&CK Mapping

---

## Overview

Detection Lab 1.0 is a standalone virtual environment designed to explore detection technologies such as endpoint detection and response (EDR), intrusion detection systems (IDS), and centralized logging. This lab supports hands-on experimentation with security tooling and maps findings to MITRE ATT&CK techniques.

---

## Objectives

- Deploy and configure open-source EDR/IDS tools
- Capture and analyze malicious behavior
- Map detections to MITRE ATT&CK
- Generate real-world logging for analysis
- Practice detection engineering and log analysis

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

> ![Detection Lab Topology](./diagram/detection-lab1-topology.drawio.png)  
*A high-level view of the environment architecture.*

---

## Installation Notes

_(Coming soon: Step-by-step installation walkthroughs)_

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
| Command & Control | T1071.001 Web Traffic | Zeek             |

---

## Screenshots

_(Screenshots of detections and dashboards will be added here.)_

---

## Author Notes

This project is part of my cybersecurity training and portfolio development. All tools used are open-source and installed in a local virtual lab for educational purposes.
