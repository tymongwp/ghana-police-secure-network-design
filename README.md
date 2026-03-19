# ghana-police-secure-network-design
# # Securing Ghana Police Data Communication

## Overview
This project focuses on designing and implementing a secure network for the Ghana Police Service to protect sensitive data such as criminal records, staff information, and investigation reports.

## Objectives
- Secure communication between headquarters and regional offices
- Protect sensitive data in storage and transit
- Implement strong authentication and access control
- Enable secure remote access for officers

## 🧠 Tools Used
- VPN (Secure remote access)
- Wireshark (Network traffic analysis)
- ADAudit Plus (User activity monitoring and auditing)

## Network Security Design
- Centralized servers located in Accra
- Secure connections from 16 regional headquarters
- Network segmentation to control access
- Firewall protection and monitoring

## 🔐 Security Implementation

### 1. Secure Remote Access (VPN)
A VPN was configured to ensure encrypted communication for police officers accessing the network remotely.

### 2. Network Monitoring (Wireshark)
Wireshark was used to analyze network traffic and detect suspicious activity.

### 3. User Activity Monitoring (ADAudit Plus)
ADAudit Plus was implemented to monitor login activities and detect unauthorized access attempts.

## System Hardening

### Workstation Hardening
- Disabled guest account
- Enforced strong password policies
- Enabled firewall and antivirus

### Server Hardening
- Disabled unnecessary services
- Restricted administrative access
- Secured file permissions

## Risks Identified
- Unauthorized access to sensitive data
- Data interception during transmission
- Insider threats

## Mitigation Measures
- Use of VPN for secure communication
- Strong authentication mechanisms
- Continuous monitoring of network activity

## Evidence
Screenshots of:
- VPN connection
- Wireshark traffic analysis
- ADAudit Plus logs
- System hardening configurations

## Real-World Application
This project demonstrates how law enforcement agencies can secure distributed networks and protect sensitive information while supporting remote operations.

## 👨‍💻 Author
Tymon A-A (C|CT)
