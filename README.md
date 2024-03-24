# Active Directory and Detection Home Lab

## Objective

The Active Directory and Detection Lab aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience deepened my understanding of network security, attack patterns, and defensive strategies.

### Skills Learned

- Advanced understanding of SIEM concepts and practical application
- Proficiency in analyzing and interpreting network logs
- Ability to generate and recognize attack signatures and patterns
- Enhanced knowledge of network protocols and security vulnerabilities
- Development of critical thinking and problem-solving skills in cybersecurity

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis
- Network analysis tools (such as Wireshark) for capturing and examining network traffic
- Telemetry generation tools to create realistic network traffic and attack scenarios

## Steps

- Setting up an Active Directory environment (Domain: MyHomeLab, Network: 192.168.10.0/24)
- Implementing Splunk (Server IP: 192.168.10.10) to ingest events and analyze telemetry
- Utilizing Kali Linux (Attacker: 192.168.10.250) to simulate attacks
- Deploying Atomic Red Team on a Windows 10 target machine
- Understanding how data flows within the lab for effective threat detection

Attached is a diagram illustrating the architecture of my home lab. It consists of two servers, a switch, a router, an attacker machine (Kali Linux), and a target machine, all connected to the cloud/internet.

The Active Directory server (IP: 192.168.10.7) is equipped with a Splunk Universal Forwarder and Sysmon for enhanced monitoring. The target machine, a Windows 10 system, hosts Splunk Universal Forwarder, Sysmon, and Atomic Red Team for comprehensive testing.


![my AD HomeLab drawio](https://github.com/daveittt/Active-Directory-and-Detection-Home-Lab/assets/159277610/7b61d8cc-14d5-4f8e-879f-aa5242285454)

*Ref 1: Network Diagram*
