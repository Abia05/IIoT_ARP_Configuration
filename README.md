# IIoT_ARP_Configuration

🔹 Aim

To configure and analyze the working of the Address Resolution Protocol (ARP) in an Industrial IoT network simulation environment using Cisco Packet Tracer (or equivalent), demonstrating how devices resolve IP addresses into MAC addresses for communication.

🔹 Problem Statement

In Industrial IoT networks, multiple devices (sensors, actuators, controllers, and gateways) communicate with each other over Ethernet or wireless networks. For proper communication, devices must translate IP addresses into physical (MAC) addresses. This process is handled by ARP.
Without ARP configuration and verification, devices cannot establish correct end-to-end communication, resulting in data transmission failures in IIoT systems.

🔹 Scope of the Solution

Demonstrates ARP working in a simulated IIoT environment.
Helps understand how devices maintain ARP tables to resolve IP-to-MAC mappings.
Provides the foundation for secure and reliable communication in industrial automation systems.
Can be extended to study ARP spoofing attacks and mitigation in IIoT.

🔹 Required Components
Hardware (Simulated)
PCs (representing IIoT devices)
Switch
Router (optional, for inter-network ARP testing)
Industrial Controllers / IoT nodes (represented via PCs in Packet Tracer)
Software & Tools
Cisco Packet Tracer (preferred for ARP simulation)
Alternative Tools: GNS3 / TinkerCad (basic network simulation) / Fritzing (circuit-level visualization)
IDE/Editor: VS Code (for documentation and GitHub management)
GitHub (for project upload and version control)

🔹 Simulated Circuit / Network Topology

Setup in Cisco Packet Tracer:
Two PCs connected to a switch.
Assign IP addresses to both PCs (e.g., PC1 → 192.168.1.2, PC2 → 192.168.1.3).
Ping PC2 from PC1.
Observe ARP table on PC1 using command:
arp -a
Verify that the MAC address of PC2 is resolved.



