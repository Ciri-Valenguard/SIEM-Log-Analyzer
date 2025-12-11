SIEM Log Triage Simulator (Security Operations Center Portfolio Project)

Project Summary

This project is an interactive, single-page web application that simulates the core functionality of a Security Information and Event Management (SIEM) dashboard. It is specifically designed to showcase entry-level SOC Analyst skills, focusing on Alert Triage, Log Analysis, and Incident Risk Scoring—the most critical competencies for junior security roles.

The application uses realistic mock data to simulate real-time log ingestion, processing, and prioritization, demonstrating practical proficiency in handling security events.

Core Features

Simulated Log Ingestion: Loads mock security logs from diverse sources (Firewall, Web Server, Endpoint).

Risk Scoring: Automatically assigns severity levels (High, Medium, Low) to logs, simulating a correlation engine for immediate incident prioritization.

Triage Search/Filtering: Supports interactive filtering using common SIEM-like queries (e.g., risk:high, source:web, ip:103.20.55.180).

Metrics Panel: Provides real-time event counts and risk statistics to manage triage workload effectively.

Key Skills Demonstrated for Interviewers

This project is built to demonstrate the following critical skills:

Log Analysis: Ability to read, interpret, and process structured log data from multiple source types.

Incident Triage: Using risk scoring to prioritize P1 and P2 incidents (e.g., SQL Injection, Geo-Blocked Botnet).

SIEM Proficiency: Understanding of SIEM workflow, log aggregation, and search functionality.

Threat Identification: Identifying indicators of compromise (IOCs) such as brute force attempts and command-and-control (C2) traffic.

Simulated Threat Scenarios

The included mock data directly addresses common, high-priority attack vectors:

SQL Injection Attempt: A high-risk alert originating from the Web source, requiring immediate investigation and containment.

External Botnet Connection: A geo-blocked connection from a known malicious IP address, logged by the Firewall.

Brute Force Detection: Multiple failed login attempts (Medium risk) captured by the Endpoint system, indicating a password guessing attack.

Running the Project

This project is a single, self-contained HTML file (siem_dashboard.html) and requires no backend or complex setup.

Clone the repository.

Open siem_dashboard.html directly in any web browser.
