# project---5

# Enumeration Project

I am working on a project that's all about trying out things with **CEH v13 – Module 04**. This project is about finding out information from the services on a network after we have scanned the network.

The project is really about looking for information that's out in the open from common network services like SMB, NetBIOS SMTP, NFS and RPC.

 We are using Linux tools that everyone, in the industry uses to do this in a lab where we can try things out safely.

---

# Project Objectives

- Understand the Enumeration phase of Ethical Hacking.
- Learn how to interact with network services safely.
- Enumerate SMB, NetBIOS, SMTP, NFS, and RPC services.
- Identify exposed resources and service information.
- Build practical enumeration skills using Kali Linux.

---

# Environment

- Operating System: Kali Linux
- Target Machine: Metasploitable 2
- Shell: Bash
- Virtualization: VirtualBox
- Version Control: Git & GitHub

---

# Repository Structure

```text
enumeration-project/
│── README.md
│── notes.md
│── screenshots/
└── LICENSE
```

---

# Project Modules

## Part 1 – Introduction to Enumeration & Banner Grabbing

- Enumeration Fundamentals
- Banner Grabbing
- HTTP Banner
- SSH Banner
- HTTP Methods

---

## Part 2 – SMB & NetBIOS Enumeration

- SMB Shares
- NetBIOS Information
- Anonymous Enumeration
- Shared Resources

---

## Part 3 – SMTP Enumeration

- SMTP Banner
- EHLO
- HELP Command
- VRFY Command
- SMTP Capabilities

---

## Part 4 – NFS Enumeration

- Exported Shares
- RPC Services
- Mount Information
- NFS Enumeration

---

# Tools Used

- Netcat (nc)
- smbclient
- enum4linux
- rpcclient
- showmount
- rpcinfo
- curl

---

# Skills Demonstrated

- Banner Grabbing
- SMB Enumeration
- NetBIOS Enumeration
- SMTP Enumeration
- NFS Enumeration
- RPC Enumeration
- Service Information Gathering
- Network Service Analysis

---

# Learning Outcomes

After completing this project, I gained practical experience in:

- Understanding the Enumeration phase.
- Enumerating SMB and NetBIOS services.
- Gathering information from SMTP servers.
- Identifying exported NFS shares.
- Understanding the relationship between NFS and RPC services.
- Documenting enumeration findings professionally.

---

# Career Relevance

The practical skills demonstrated in this project are applicable to:

- SOC Analyst (L1)
- Cybersecurity Analyst
- Penetration Tester (Junior)
- Vulnerability Assessment
- Network Security

---

# Lab Notes

Some enumeration protocols covered in CEH Module 04, such as **SNMP** and **LDAP**, were not demonstrated in this repository because the selected lab environment (Metasploitable 2) did not provide these services by default.

 The project focuses on services that were available and could be practically demonstrated.

---

# Ethical Notice

All demonstrations in this repository were performed in an authorized lab environment using Kali Linux and Metasploitable 2. This project is intended solely for cybersecurity education and ethical learning.

---

# Future Learning

The next project continues with:

**CEH v13 – Module 05: Vulnerability Analysis**

where the information collected during enumeration will be used to identify potential security weaknesses.

---

# Author

**Kranthi Kumar**

Aspiring SOC Analyst | CEH Student | Cybersecurity Enthusiast

GitHub: https://github.com/kranthi778

---
