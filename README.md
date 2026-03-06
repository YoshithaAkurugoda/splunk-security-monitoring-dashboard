# Splunk Security Monitoring Dashboard

## Overview
This project demonstrates the design and analysis of a security monitoring dashboard using Splunk. The dashboard is designed to help security analysts detect suspicious activity within an enterprise network environment.

The system focuses on identifying abnormal external connections, monitoring user activity, and analyzing network traffic patterns to detect potential cyber threats.

The dashboard was designed for a fictional financial organization, Sutrefia (Sunken Treasure Financials Australia), which handles sensitive customer information and must comply with strict cybersecurity policies.

## Objectives
The main objective of this project was to demonstrate how Security Information and Event Management (SIEM) tools like Splunk can be used to monitor network activity and identify potential security threats.

Key goals included:

- Visualizing network traffic patterns
- Detecting suspicious external connections
- Monitoring user activity across systems
- Supporting incident investigation using log analysis

## Technologies Used
- Splunk (SIEM platform)
- Log analysis
- Security monitoring dashboards
- Network event data

## Dashboard Panels

### 1. Top External Connections by Host
This panel identifies internal hosts that make the highest number of connections to external systems.  
It helps detect:

- possible data exfiltration
- compromised machines
- suspicious outbound traffic

### 2. External Connections Over Time
This visualization shows the volume of external connections across time.

Security analysts can use this panel to detect:

- unusual traffic spikes
- potential attack windows
- abnormal activity patterns

### 3. External Port Usage Breakdown
This panel analyzes which network ports are being used during external communications.

It helps identify:

- unauthorized services
- abnormal port usage
- potential command-and-control traffic

### 4. Top Users by Event Count
This panel identifies users generating the highest number of system events.

This information can reveal:

- compromised accounts
- suspicious user behaviour
- insider threats

## Security Policies Considered
The dashboard aligns with security principles based on the **Australian Cyber Security Centre (ACSC) Information Security Manual**.

Key policies considered include:

- Endpoint security
- Unauthorized software detection
- Continuous monitoring of network activity

## Learning Outcomes
Through this project I developed practical knowledge in:

- Security Information and Event Management (SIEM)
- Log monitoring and analysis
- Threat detection using dashboards
- Security policy enforcement


## Author
Yoshitha Akurugoda  
Cybersecurity Undergraduate
