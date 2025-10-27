# 🛡️ Incident Response and Forensics Analysis

This project simulates a cybersecurity incident and demonstrates the complete lifecycle of incident response, forensic investigation, and post-incident review using the **Autopsy digital forensics tool**.

## 📌 Project Overview

The simulation involves a mock security breach where suspicious files are planted to mimic a phishing attack and data leak. The goal is to walk through the steps a cybersecurity analyst would take to identify, isolate, investigate, and document the incident.

## 🧪 Simulated Threat Scenario

A folder named `FakeIncident` was created containing the following suspicious files:

- `malware.exe`: A fake executable mimicking malware behavior.
- `invoice.pdf.exe`: A disguised executable intended to trick users into launching it.
- `passwords.txt`: A text file containing fake credentials.
- `system_log.txt`: A fabricated system log referencing suspicious activity and a rogue user account (`hacker123`).

## 🧯 Incident Response Strategy

Upon detection of the suspicious files:

1. The system was isolated to prevent further compromise.
2. The incident was documented.
3. A forensic investigation was initiated using Autopsy.

## 🔍 Forensic Analysis with Autopsy

Autopsy was used to analyze file metadata, contents, and system artifacts. Key findings include:

- Detection of executables masquerading as documents.
- Evidence of fake credentials and suspicious log entries.
- Identification of a rogue user (`hacker123`) and timestamped activity.

## 📈 Post-Incident Review

The response was successful in identifying and containing the threat. Recommendations for improvement include:

- Implementing real-time alert systems.
- Enhancing user awareness and training.
- Automating incident reporting and escalation workflows.

## 🎯 Learning Outcomes

This hands-on exercise provided practical experience in:

- Simulating cybersecurity threats.
- Applying digital forensic tools.
- Documenting and analyzing incidents.
- Strengthening incident response protocols.

## 📄 Report

The full analysis is documented in `Incidence_Response_Report.pdf`.
