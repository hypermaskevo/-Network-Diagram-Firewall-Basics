# 🔌 Cisco Packet Tracer Lab – Day 01: Network Diagram & Firewall Basics

## 📘 Overview

This project is based on the Day 1 lab exercise for Cisco Packet Tracer practice. It demonstrates a simple but structured enterprise network with two locations (New York and Tokyo) connected via the Internet, using routers, switches, firewalls, and endpoints. It also introduces the concept of external threats with an 'Attacker' laptop.

## 🧱 Topology Components

The following network devices were used:

- 🖥️ **PCs (x2)** – End users at New York branch  
- 💻 **Laptop (x1)** – Representing a potential attacker  
- 🌐 **Cisco 2911 Routers (x2)** – One at each branch  
- 🔁 **Cisco 2960 Switches (x2)** – Local network access at each branch  
- 🔥 **Cisco ASA 5505 Firewalls (x2)** – Network protection at both sites  
- 🖥️ **Servers (x2)** – Hosted in the Tokyo Branch  

## 🗺️ Logical Topology

[PC1] [PC2]
| |
+---SW1---+
|
[Router1]
|
[FW1]---[Internet]---[FW2]
|
[Router2]
|
SW2
/
[SRV1] [SRV2]
        [Attacker Laptop] connected to Internet switch
        
## ⚙️ Setup Instructions

1. Use **Packet Tracer's "Automatically Choose Connection Type"** to connect all devices.
2. Assign appropriate IP addresses (not included in this diagram).
3. Configure routing between routers.
4. Set up basic firewall rules on both firewalls.
5. Simulate ping/traffic from attacker to test firewall protections.

## 🎯 Learning Objectives

- Understand the basic layout of enterprise branch connectivity
- Learn to configure routers and firewalls for inter-branch communication
- Visualize how an external attacker might try to enter the network
- Practice logical segmentation and firewall filtering

## 📁 File

- `Day01-Lab.pkt` – The full Cisco Packet Tracer file for this setup (rename your file accordingly)

## ✅ Status

- [x] Topology built  
- [ ] IP addressing and routing  
- [ ] Firewall ACLs  
- [ ] Attack simulation test

---

**Author:** Yurii Vysotskyi
**Date:** May 2025  
