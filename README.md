# Modi-Joy-Task-4

# Task 4 - Setup and Use a Firewall on Windows

## Objective
Configure and test basic firewall rules to allow or block traffic.

## Tools Used
- Windows Defender Firewall
- Windows Defender Firewall with Advanced Security

## Steps Performed

1. Opened Windows Defender Firewall.
2. Viewed existing inbound firewall rules.
3. Created a new inbound rule to block TCP Port 23 (Telnet).
4. Tested the firewall rule.
5. Removed the test rule after verification.

## Why Port 23 Was Blocked
Port 23 is used by Telnet, which sends data in plain text and is considered insecure.

## Outcome
Learned how firewall rules filter network traffic and how to create, test, and remove firewall rules in Windows.

## Interview Questions

### What is a firewall?
A firewall is a security system that monitors and controls incoming and outgoing network traffic based on predefined rules.

### Difference between stateful and stateless firewall?
A stateful firewall tracks active connections, while a stateless firewall examines each packet independently.

### What are inbound and outbound rules?
Inbound rules control incoming traffic, while outbound rules control traffic leaving the system.

### Why block port 23?
Port 23 is used by Telnet, which is insecure because it transmits data without encryption.

### How does a firewall improve security?
It blocks unauthorized access and helps protect systems from network attacks.
task-4-firewall
