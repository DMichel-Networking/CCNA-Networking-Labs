# CCNA Networking Labs

## Overview

This repository documents my hands-on progression through the **Cisco Certified Network Associate (CCNA 200-301)** curriculum.

Rather than focusing solely on memorizing networking concepts and Cisco IOS commands, this repository contains practical labs designed to help me **configure, analyze, verify, and troubleshoot networks from the ground up**.

My goal is to develop a deep understanding of how networks operate while building the practical skills necessary for a career in **Network Engineering**.

---

## Lab Objectives

For each major CCNA topic, my goal is to be able to:

- Configure networking technologies from scratch
- Verify that configurations are functioning correctly
- Explain how and why networking technologies work
- Analyze network traffic and protocol behavior
- Troubleshoot intentionally broken configurations
- Use packet analysis to understand network communication
- Document configurations, results, and lessons learned

A lab is not considered complete simply because connectivity succeeds.

---

## Lab Methodology

Each lab is designed around five primary areas of mastery.

### 1. Configure

Can I build and configure the network without relying heavily on step-by-step instructions?

### 2. Verify

Can I use Cisco IOS commands and networking utilities to prove that the network is functioning correctly?

### 3. Explain

Can I explain what is happening at each relevant layer of the **TCP/IP model** and why?

### 4. Troubleshoot

Can I identify and resolve configuration or connectivity problems using a structured troubleshooting process?

### 5. Analyze

Can I examine packets and frames using **Wireshark** and **Cisco Packet Tracer Simulation Mode** and explain the important header fields and protocol behavior?

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
- ARP
- ICMP
- TCP & UDP
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

## Core Networking Concepts

The labs in this repository progress from networking fundamentals into increasingly advanced switching, routing, security, and automation concepts.

Particular emphasis is placed on understanding:

- TCP/IP encapsulation and de-encapsulation
- Ethernet frames and MAC addressing
- ARP and Layer 2 address resolution
- IPv4 and IPv6 addressing
- Subnetting and CIDR notation
- TCP and UDP behavior
- Routing decisions and routing tables
- Packet forwarding between networks
- Switching and MAC address tables
- VLAN segmentation
- IEEE 802.1Q trunking
- Inter-VLAN routing
- Spanning Tree Protocol
- Static routing
- Dynamic routing
- OSPF
- DHCP and DNS
- NAT and PAT
- Access Control Lists
- Network troubleshooting
- Packet analysis
- Network security
- Network automation

---

## TCP/IP Fundamentals

A major focus of this repository is understanding what actually happens when information travels across a network.

The basic encapsulation process is:

`Data → Segment → Packet → Frame → Bits`

### Application Layer

Creates the original application data.

### Transport Layer

Adds transport-layer information.

TCP uses a **segment**.

UDP uses a **datagram**.

### Network Layer

Adds the IP header and provides logical addressing and routing.

The Layer 3 PDU is a **packet**.

### Data Link Layer

Adds Layer 2 addressing and Ethernet framing information.

The Layer 2 PDU is a **frame**.

### Physical Layer

Transmits the information as bits using physical signals across the network medium.

---

## Packet Analysis

Whenever possible, labs go beyond successful pings and configurations by examining the actual network traffic.

Using **Wireshark** and **Packet Tracer Simulation Mode**, I analyze concepts such as:

- Source and destination MAC addresses
- Source and destination IP addresses
- EtherType
- ARP requests and replies
- ICMP messages
- IPv4 headers
- TTL
- TCP source and destination ports
- TCP flags
- TCP sequence numbers
- TCP acknowledgment numbers
- UDP datagrams
- DNS queries and responses
- DHCP DORA
- Encapsulation and de-encapsulation

This allows me to connect Cisco configurations and networking concepts with what is actually occurring at the packet and frame level.

---

## Lab Organization

Labs are organized by the CCNA chapter and networking topic being studied.

Each chapter contains multiple hands-on exercises that progress from fundamental concepts into configuration, packet analysis, verification, and troubleshooting.

Individual labs may contain:

- README documentation
- Cisco Packet Tracer files
- Network topology screenshots
- Cisco IOS configuration screenshots
- Verification results
- Wireshark captures
- Packet Tracer Simulation Mode analysis
- Troubleshooting documentation

---

## Lab Documentation

Each completed lab will document:

- Lab objective
- Network topology
- IP addressing
- Device configuration
- Cisco IOS commands
- Connectivity testing
- Verification
- Packet analysis
- Troubleshooting
- Screenshots
- Key concepts learned
- Skills demonstrated
- Lessons learned

---

## Skills Being Developed

- Cisco IOS Configuration
- TCP/IP Fundamentals
- IPv4 & IPv6 Addressing
- Subnetting
- Ethernet
- Layer 2 Switching
- Layer 3 Routing
- VLAN Configuration
- Trunk Configuration
- Inter-VLAN Routing
- Static Routing
- OSPF
- Access Control Lists
- NAT/PAT
- DHCP
- DNS
- Wireless Networking
- Packet Analysis
- Wireshark
- Cisco Packet Tracer
- Network Verification
- Network Troubleshooting
- Network Documentation
- Network Automation

---

## Repository Status

**Status:** Active / In Progress

This repository will continue to grow as I progress through the **CCNA 200-301** curriculum and complete additional configuration, packet analysis, verification, and troubleshooting labs.

---

## Long-Term Goal

The purpose of this repository is not simply to prepare for the **CCNA 200-301 exam**.

The larger goal is to develop a strong practical foundation in networking and demonstrate continued progression toward becoming a **Network Engineer**.

By combining networking theory with configuration, troubleshooting, and packet-level analysis, this repository will document both my CCNA studies and the development of practical networking skills.
