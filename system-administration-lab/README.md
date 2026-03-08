# System Administration and Security Fundamentals Lab

## Overview

This lab demonstrates fundamental system administration and security tasks across Linux and Windows environments.

The exercise focuses on user account management, access control, firewall configuration, and endpoint security monitoring.

---

## Environment

- Ubuntu Linux (WSL)
- Windows administrative tools
- Windows Defender Firewall
- Windows Defender Antivirus

---

## Task 1 – Linux User Creation

A new user account was created using the Linux command line.

Command used:
sudo adduser batman

The account creation was verified using:
cat /etc/passwd | grep batman

---

## Task 2 – Windows User Management

Using **Computer Management**, the user account **Batman** was created and verified.

This demonstrates basic identity and access management within Windows systems.

---

## Task 3 – Group Membership Assignment

The user **Batman** was added to the **Accounting group**.

This demonstrates how organizations manage permissions using group-based access control.

---

## Task 4 – Firewall Configuration

A firewall rule was configured allowing **Port 80 (HTTP)** inbound traffic.

This demonstrates basic network security configuration.

---

## Task 5 – Endpoint Security Scan

A system scan was performed using **Windows Defender** to verify the system was free from threats.

---

## Security Concepts Demonstrated

- Identity and Access Management
- Access control
- Firewall configuration
- Endpoint protection
- System administration fundamentals

---

## Skills Practiced

- Linux command line
- Windows user administration
- Firewall rule configuration
- Endpoint security monitoring
