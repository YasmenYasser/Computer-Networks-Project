# 🌐 Computer Networks Project   
**Faculty of Computer Science**   
**Project_S25**  

---

## 🚀 Overview

This repository contains the **full implementation** of the Computer Networks project for CSC230 at Misr International University. The project delivers a complete, professionally-configured network topology, with all designs, configurations, and documentation fully implemented and verified.

---

## 📑 Table of Contents

- [Objectives](#objectives)
- [Project Files](#project-files)
- [Network Design](#network-design)
- [Implementation Steps](#implementation-steps)
- [Testing & Screenshots](#testing--screenshots)
- [Troubleshooting Guide](#troubleshooting-guide)
- [Credits](#credits)

---

## 🎯 Objectives

- Design and implement a VLSM addressing scheme
- Build and configure the network and devices
- Set up Layer 2 (VLANs, trunking, EtherChannel)
- Configure OSPFv2 & EIGRP routing, with redistribution
- Implement DHCP, NAT (PAT & Static), and IPsec VPN
- Enable network management (NTP, Syslog, DNS, Email, Web)
- Set up and secure a Wireless Home Router
- Verify connectivity and provide complete documentation

---

## 📦 Project Files

| File/Folder         | Description                                               |
|---------------------|----------------------------------------------------------|
| **Project_S25.pkt** | Main Cisco Packet Tracer topology file                   |
| **/docs/**          | Documentation, screenshots, and additional materials     |

---

## 🗺️ Network Design

### VLSM Addressing Scheme

- **Base Network Address:** `10.1.0.0/12`
- Subnetting tailored for VLANs and point-to-point links.

> *Full subnet and address allocation details are included in the `/docs` directory.*

---

## 🛠️ Implementation Steps

### 1. VLSM Addressing Scheme
- Designed and allocated IP subnets to all VLANs and networks.
- Populated address tables for all devices.

### 2. Network Build & Device Configuration
- Constructed topology in Packet Tracer.
- Configured hostnames, secure passwords, SSH, and banners.
- Assigned IPs and default gateways.

### 3. Layer 2 & Host Support
- Created VLANs, trunk links, and EtherChannels (LACP).
- Configured inter-VLAN routing and verified connectivity.

### 4. Routing Protocols
- OSPFv2 (process ID 100) and EIGRP (AS 10) setup.
- Configured redistribution, static routes, and default routes.
- Verified routing tables and protocol operation.

### 5. DHCP Server
- Set up DHCP on the main and branch segments.
- Configured DHCP relay agents and tested host assignments.

### 6. NAT Configuration
- Implemented Dynamic NAT with PAT and Static NAT.
- Verified NAT operation and translations.

### 7. Network Management
- Enabled NTP and Syslog on all devices.
- Configured DNS, web, and email servers for `miu.edu.eg`.

### 8. Site-to-Site IPsec VPN
- Established a secure VPN tunnel between MIU-GW and Branch-GW.

### 9. Wireless Home Router
- SSID: `MIU-CSC230` (2.4 GHz), WPA2/AES, passphrase: `miu_csc230`.
- Connected wireless clients and verified access.

### 10. Connectivity Verification
- Ping and traceroute tests between all devices.
- Verified interfaces and routing tables.
- Screenshots included in `/docs`.

### 11. Documentation & Handover
- Full configuration steps and troubleshooting included in `/docs`.

---

## 🖼️ Testing & Screenshots

All test results (pings, traceroutes, routing tables, interface summaries) and diagrams are available in the `/docs` directory.

---

## 🛡️ Troubleshooting Guide

A summary of common issues and solutions encountered during implementation is provided in `/docs/troubleshooting.md`.

---

## 👥 Credits

- Guided by **Dr. Mostafa Abdelrahman**, MIU

---

> **Tip:**  
> For configuration files, exported device scripts, and all documentation, see the `/docs` folder and `Project_S25.pkt` file in this repository.

---
