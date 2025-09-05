# IIoT: Simple LAN & Address Resolution Protocol (ARP)

## Aim
To construct a simple LAN using Cisco Packet Tracer and study the concept and operation of Address Resolution Protocol (ARP).

## Problem Statement
Devices in a LAN communicate using IP addresses, but actual communication happens via MAC addresses. ARP maps IP addresses to MAC addresses. This project demonstrates ARP operation in a simulated LAN.

## Scope
- Demonstrates LAN construction
- Shows ARP table entries
- Teaches how to clear and reload ARP cache
- Foundation for secure IIoT networking

## Components
- **Hardware (Simulated):**
  - 2 PCs
  - 1 Switch (8-Port 2960)
  - 2 LAN cables
- **Software:**
  - Cisco Packet Tracer
  - GitHub (for documentation)

## Topology
![LAN Topology](LAN_Topology.png)

## Configuration Steps
1. Connect PCs to the switch using LAN cables.
2. Assign IP addresses:
   - PC0 → 192.168.1.2
   - PC1 → 192.168.1.3
3. Ping between PCs.
4. Use `arp -a` to display ARP table.
5. Use `arp -d` to clear cache, then re-ping.

## Demo
🎥 [Watch Demo Video](Demo.mp4)

## Files in Repository
- `README.md` → Documentation  
- `LAN_ARP.pkt` → Cisco Packet Tracer simulation  
- `LAN_Topology.png` → Network topology screenshot  
- `Demo.mp4` → Demo video of ARP operation
