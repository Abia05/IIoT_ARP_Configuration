# IIoT_ARP_Configuration

🔹 Aim

To configure and analyze the working of the Address Resolution Protocol (ARP) in an Industrial IoT network simulation environment using Cisco Packet Tracer (or equivalent), demonstrating how devices resolve IP addresses into MAC addresses for communication.

🔹 Problem Statement

In Industrial IoT networks, multiple devices (sensors, actuators, controllers, and gateways) communicate with each other over Ethernet or wireless networks. For proper communication, devices must translate IP addresses into physical (MAC) addresses. This process is handled by ARP.
Without ARP configuration and verification, devices cannot establish correct end-to-end communication, resulting in data transmission failures in IIoT systems.

🔹 Scope of the Solution

- Understand LAN construction using Cisco Packet Tracer.
- Study ARP operation and ARP table updates when PCs communicate.
- Learn how to clear ARP cache and verify re-learning.
- Foundation for understanding advanced networking in IIoT and cybersecurity (e.g., ARP spoofing).

🔹 Required Components

Hardware (Simulated in Cisco Packet Tracer)
2 PCs (PC0 and PC1)
1 Switch (8-port)
2 Straight-Through LAN cables

Software
Cisco Packet Tracer (for simulation)
GitHub (for project upload and documentation)

🔹 Network Topology

PC0  ────────┐
              │
         8-Port Switch
              │
PC1  ────────┘


🔹 Configuration Steps

Step 1: Setup Topology
- Drag and drop 2 PCs and 1 Switch (2960-8TT) into the workspace.
- Connect PC0 and PC1 to the switch using Copper Straight-Through cables.

Step 2: Assign IP Addresses
- PC0 → IP: 192.168.1.2, Subnet Mask: 255.255.255.0
- PC1 → IP: 192.168.1.3, Subnet Mask: 255.255.255.0

Step 3: Verify Connectivity
- On PC0, open Command Prompt → type: ping 192.168.1.3
- Successful ping indicates connectivity.

Step 4: Observe ARP Operation
- On PC0, type: arp -a
- This shows the MAC address of PC1.
- clear ARP cache with: arp -d
- Then ping again and check ARP table → it re-learns the MAC address.


