````markdown
# CCNA Networking Labs

## Overview

A hands-on networking portfolio documenting my progression through the **Cisco Certified Network Associate (CCNA 200-301)** curriculum.

Rather than focusing solely on memorizing concepts and Cisco IOS commands, this repository documents practical labs designed to help me **configure, analyze, verify, and troubleshoot networks from the ground up**.

My goal is to develop a deep understanding of how networks operate and build the practical skills necessary for a career in **Network Engineering**.

---

## Lab Objectives

For each major CCNA topic, my goal is to be able to:

- Configure the technology from scratch
- Verify that the configuration is functioning correctly
- Explain why and how the technology works
- Analyze the underlying network traffic and protocols
- Troubleshoot intentionally broken configurations
- Document the results and lessons learned

Labs progress from fundamental exercises into more complex configuration, packet analysis, and troubleshooting scenarios.

---

## Tools & Technologies

Throughout these labs, I will be working with:

- Cisco Packet Tracer
- Cisco IOS CLI
- Wireshark
- Windows networking utilities
- Linux networking utilities
- Physical Cisco networking equipment
- TCP/IP
- Ethernet
- IPv4 & IPv6
- VLANs & Trunking
- Spanning Tree Protocol
- Static & Dynamic Routing
- OSPF
- DHCP
- DNS
- NAT/PAT
- Access Control Lists (ACLs)
- Wireless Networking
- Network Security
- Network Automation

---

## Lab Methodology

A lab is not considered complete simply because connectivity succeeds.

For each topic, I aim to answer five questions:

### 1. Configure

Can I build and configure the network without relying heavily on step-by-step instructions?

### 2. Verify

Can I use Cisco IOS commands and networking utilities to prove that the configuration is functioning correctly?

### 3. Explain

Can I explain what is happening at each relevant layer of the TCP/IP model and why?

### 4. Troubleshoot

Can I identify and resolve configuration or connectivity problems using a structured troubleshooting process?

### 5. Analyze

Can I examine packets and frames using tools such as Wireshark and Packet Tracer Simulation Mode and explain the important header fields and protocol behavior?

---

## Lab Directory

```text
CCNA-Networking-Labs/
│
├── Chapter-01-Networking-Fundamentals/
│   ├── Lab-01-TCP-IP-Encapsulation/
│   ├── Lab-02-ARP/
│   ├── Lab-03-Ethernet-Frames/
│   └── ...
│
├── Chapter-02/
│
├── Chapter-03/
│
└── ...
````

Each individual lab may contain:

```text
Lab-XX-Lab-Name/
│
├── README.md
├── packet-tracer-file.pkt
└── screenshots/
```

Individual lab README files document the **objective, topology, addressing, configuration, verification, packet analysis, troubleshooting, and lessons learned**.

---

## Core Networking Concepts

The labs in this repository will explore networking concepts at increasingly deeper levels.

### TCP/IP Encapsulation

```text
Application Data
       ↓
TCP Segment / UDP Datagram
       ↓
IP Packet
       ↓
Ethernet Frame
       ↓
Bits / Physical Transmission
```

Particular emphasis is placed on understanding:

* TCP/IP encapsulation and de-encapsulation
* Ethernet frames and MAC addressing
* ARP and Layer 2 address resolution
* IPv4 and IPv6 addressing
* Subnetting and CIDR
* TCP and UDP behavior
* Routing decisions and routing tables
* Packet forwarding between networks
* Switching and MAC address tables
* VLAN segmentation
* IEEE 802.1Q trunking
* Inter-VLAN routing
* Spanning Tree Protocol
* Static routing
* OSPF
* DHCP and DNS
* NAT and PAT
* Access Control Lists
* Network troubleshooting
* Packet analysis

---

## Packet Analysis

Whenever possible, labs go beyond successful pings and configurations by examining the actual network traffic.

Using **Wireshark** and **Packet Tracer Simulation Mode**, I analyze concepts such as:

* Source and destination MAC addresses
* Source and destination IP addresses
* EtherType
* ARP requests and replies
* ICMP messages
* IPv4 headers
* TTL
* TCP ports
* TCP flags
* TCP sequence and acknowledgment numbers
* UDP datagrams
* DNS queries and responses
* DHCP DORA
* Encapsulation and de-encapsulation

This allows me to connect Cisco configurations and networking concepts with what is actually occurring at the packet and frame level.

---

## Lab Documentation

Individual labs will include documentation covering:

* Lab objective
* Network topology
* IP addressing
* Device configuration
* Cisco IOS commands
* Connectivity testing
* Verification
* Packet analysis
* Troubleshooting
* Screenshots
* Key takeaways
* Lessons learned

---

## Skills Being Developed

* Cisco IOS Configuration
* Network Troubleshooting
* TCP/IP
* Ethernet
* IPv4 & IPv6
* Subnetting
* Routing
* Switching
* VLAN Configuration
* Packet Analysis
* Wireshark
* Cisco Packet Tracer
* Network Verification
* Network Documentation

---

## Repository Status

**Status:** Active / In Progress

This repository will continue to grow as I progress through the **CCNA 200-301** curriculum and complete additional configuration, packet analysis, and troubleshooting labs.

---

## Long-Term Goal

The purpose of this repository is not simply to prepare for the **CCNA 200-301 exam**.

The larger goal is to develop a strong practical foundation in networking and demonstrate continued progression toward becoming a **Network Engineer**.

```
```


The purpose of this repository is not simply to prepare for the CCNA exam.

The larger goal is to develop a strong practical foundation in networking and demonstrate continued progression toward becoming a Network Engineer.
