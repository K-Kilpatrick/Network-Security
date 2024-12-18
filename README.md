# Network-Security
Module 11: Introduction to Firewalls and Network Security, Introduction to Intrusion Detection, Snort, and Network Security Monitoring, Enterprise Security Management (ESM)

Module Description
This week is an introduction to network security from both a theoretical and practical standpoint. We'll explore the benefits of using defense in depth methodologies and how firewalls serve as the network's primary defense mechanism at both the perimeter and interior of the network.
A critical skill of the network defender is to not only be able to stop an attack but also to learn from them. We will explore in great detail how to establish situational awareness of our networks using detailed data analytics to learn about the tactics, techniques, and procedures (TTP) that adversaries use to successfully infiltrate networks.

Day 1 introduces firewalls. We'll examine the relationship between ports and services, including the role open ports play as the principal attack surface of networked machines. Then, we'll cover how firewalls are used to control access to a machine's open ports.

Day 2 covers intrusion detection systems (IDS) and network security monitoring (NSM). We will analyze indicators of attack and compromise (IOAs and IOCs), perform network forensics, and acquire adversarial intelligence and situational awareness of our networks.

Day 3 focuses on threat hunting using the Enterprise security management (ESM) framework of network security tools. We'll examine ESM concepts and the role of host-based endpoint telemetry, simulate investigations, and perform alert triage using Kibana.

Module Objectives

Day 1: Introduction to Firewalls and Network Security

Explain how open ports contribute to a computer's attack surface.

Use firewalls to protect a computer's open ports.

Develop and implement firewall policies using UFW and firewalld.

Day 2: Introduction to Intrusion Detection, Snort, and Network Security Monitoring

Interpret and define Snort rules and alerts.

Explain how intrusion detection systems work and how they differ from firewalls.

Use Security Onion and its suite of network security monitoring tools to trace the path of network attacks.

Collect and analyze indicators of attack and indicators of compromise using NSM tools.

Apply knowledge of NSM, Snort rules, and Security Onion to establish situational awareness within a network.

Day 3: Enterprise Security Management (ESM)

Analyze indicators of attack for persistent threats.

Use enterprise security management to expand an investigation.

Use OSSEC endpoint reporting agents as part of a host-based IDS alert system.

Investigate threats using various analysis tools.

Escalate alerts to senior incident handlers.

Lab Environment
In this module, you will use the NetSec lab environment located in Windows Azure Lab Services. RDP into the Windows RDP Host machine using the following credentials:

RDP login credentials for labs provisioned prior to 9/12/23

Username: azadmin

Password: p4ssw0rd*

RDP login credentials for labs provisioned after 9/12/23

Username: azadmin

Password: p@ssw0rdp@ssw0rd

Open Hyper-V Manager to access the following machines:

Security Onion Machine

Username: sysadmin

Password: cybersecurity

UFW Machine

Username: sysadmin

Password: cybersecurity

firewalld Machine

Username: sysadmin

Password: cybersecurity

Module Checklist
Before beginning to prep this week's lesson, be sure you have the following accessible within your lab. Please notify the curriculum team as soon as possible if any of the following is not available.

 SecOnion

 UFW

 firewalld

What to Be Aware Of

Days 2 and 3 will begin with a quick setup process so our machines can generate alert data for the lab activities.

Security+ Domains
This module covers portions of the following domains on the Security+ exam:

1.0 Attacks, Threats, and Vulnerabilities

2.0 Architecture and Design

3.0 Implementation

5.0 Governance, Risk, and Compliance

For more information about these Security+ domains, refer to the following resource: Security+ Exam Objectives

Additional Reading and Resources

These resources are provided as optional, recommended resources to supplement the concepts covered in this module.

Day 1 Resources

CSO: What is network security? Definition, methods, jobs & salaries

Cisco: What is Network Security?

Cyberseek: Career Heat Map

Day 2 Resources

CSO: What is an intrusion detection system?

Security Onion: Documentation

Security Onion: Cheat Sheet

Day 3 Resources

Kaspersky: What Is an Advanced Persistent Threat (APT)?

MITRE: ATT&CK Matrix for Enterprise

Module 11: Challenge
This module's Challenge assignment can be found in Canvas.

For this week's Challenge assignment, students will need to appropriately configure a firewall for a fictional organization.

Looking Forward
Next week, we will move into the Web Development module, followed by the Cloud Security module.
