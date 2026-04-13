# Wazuh SIEM Lab – Threat Detection & Monitoring

## Overview

This project demonstrates a Security Information and Event Management (SIEM) lab built using Wazuh. The lab monitors endpoint activity, detects security threats, and visualizes attack patterns.

## Architecture

* Wazuh Manager (Ubuntu VM)
* Wazuh Dashboard (Web Interface)
* Windows 10 Endpoint (Virtual Machine)
* VirtualBox Lab Environment

## Key Features

* Deployed Wazuh agent on a Windows endpoint
* Collected and analyzed authentication and system logs
* Simulated brute-force login attempts
* Detected failed authentication events
* Built dashboards to visualize:

  * Login activity over time
  * Targeted user accounts
  * Alert severity distribution

## Attack Simulation

Simulated brute-force login attempts using invalid credentials:

* Generated multiple failed login events
* Observed authentication anomalies
* Analyzed patterns using SIEM dashboards

## Dashboard Visualizations

* Failed login activity over time
* Most targeted user accounts
* Alert severity distribution

## Tools Used

* Wazuh (SIEM)
* OpenSearch
* VirtualBox
* Ubuntu Linux
* Windows 10

## Screenshots

### Dashboard

![Dashboard](screenshots/dashboard.png)

### Alerts (Discover View)

![Alerts](screenshots/alerts.png)

### Agents

![Agents](screenshots/agents.png)

## Conclusion

This project demonstrates hands-on experience with SIEM deployment, log analysis, threat detection, and dashboard creation in a controlled lab environment.
