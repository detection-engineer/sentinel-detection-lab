# sentinel-detection-lab

Azure Sentinel detection engineering and cloud security use cases

This repository is a work in progress documenting my learning and hands-on development of detection engineering capabilities using Microsoft Sentinel, Microsoft Entra ID telemetry, and endpoint logs.

## Background
I have a professional background in Security Operations (SOC) and Incident Response, with experience investigating alerts across endpoint, identity, and network telemetry.

This lab is part of a structured effort to deepen expertise in:
- Detection engineering
- Cloud-native security monitoring
- Identity-based threat detection
- SIEM automation and detection-as-code

## Objectives
 - Design and tune SIEM detections for identity and endpoint threats
 - Apply MITRE ATT&CK mapping to detection logic
 - Simulate real-world attack scenarios in a controlled lab
 - Explore detection-as-code concepts using Sigma and Python

## Technologies
 - Microsoft Sentinel
 - Microsoft Entra ID Sign-in & Audit Logs
 - KQL (Kusto Query Language)
 - Sigma Rules
 - Python (Detection-as-Code)
 - Sysmon (Endpoint Telemetry)

## Training Alignment
This lab work is aligned with the Microsoft SC-200 Security Operations Analyst learning path, with hands-on implementation of:
- Microsoft Sentinel analytics rules
- Identity threat detections
- Incident investigation workflows
- KQL-based threat hunting

## Planned Detection Use Cases

Initial focus is on identity and endpoint-based detections. Coverage will expand as detection logic is implemented and tuned

- Identity attacks (password spray, MFA fatigue, sign-in anomalies)
- Privileged role abuse
- Endpoint execution anomalies
