# Configuration of Address Resolution Protocol (ARP) using Cisco Packet Tracer

## Aim
To construct a simple LAN and simulate the working of the **Address Resolution Protocol (ARP)** in Cisco Packet Tracer, demonstrating how IP addresses are mapped to MAC addresses for successful communication.

---

## Problem Statement
In a computer network, devices communicate using IP addresses, but actual data transfer happens through hardware (MAC) addresses.  
Without ARP, a device cannot resolve the MAC address corresponding to an IP address, leading to communication failure.  

This project simulates ARP in a LAN setup using Cisco Packet Tracer to observe how ARP requests and replies enable devices to exchange data.

---

## Scope
- Demonstrates the role of ARP in enabling device-to-device communication within a LAN.  
- Provides hands-on experience in observing ARP tables and packet flow.  
- Educational value for students learning basic networking protocols.  
- Can be extended to study ARP cache, spoofing, and troubleshooting.  

---

## Required Components
| Category       | Items                              |
|----------------|------------------------------------|
| Software / IDE | Cisco Packet Tracer (v7.x or newer) |
| Devices        | 4 PCs, 1 Switch (8-port)            |
| Connections    | Copper Straight-through Cables      |

---

## Project Setup
1. Open **Cisco Packet Tracer**.  
2. Place **4 PCs** and **1 Switch** in the workspace.  
3. Connect each PC to the switch using straight-through cables.  
4. Assign IP addresses (e.g., 192.168.1.1 – 192.168.1.4).  
5. Ping from one PC to another to generate ARP requests.  
6. Use `arp -a` command in PCs to verify ARP table entries.  

---

## Results / Demo
- The LAN was successfully configured.  
- ARP requests and replies were exchanged when devices communicated.  
- ARP tables showed correct IP-to-MAC mappings.  
- Simulation mode displayed ARP packets broadcast across the LAN.  

---

## Files in This Repository
- **Ciscoproject.pkt** – Cisco Packet Tracer file  
- **Ciscoproject.pdf** – Detailed project report  
- **Screen Recording 2025-09-08 013047.mp4** – Screen recording of the simulation  
- **Screenshot (62).png** - Screenshot of simulation
---

## Author
(Batch No:1, 5BTCI)
