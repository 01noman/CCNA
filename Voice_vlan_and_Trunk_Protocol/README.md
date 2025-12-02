## Voice VLAN and Trunk Protocol

### Objectives:
The goal of this project is to build a segmented multi-VLAN network using a router-on-a-stick design, enabling secure inter-VLAN communication and centralized DHCP services. The topology implements VLAN 10 (Sales), VLAN 20 (IT), and VLAN 30 (Voice/IP Phone), each mapped to dedicated subinterfaces on the router. Trunk links between switches and the router carry tagged traffic for all VLANs, while access ports are assigned to their respective VLANs for end-user devices. DHCP services are provided through the router, with helper-address configuration allowing hosts in different VLANs to obtain IP addressing from the appropriate pool. The environment validates VLAN creation, trunk configuration, DHCP relay, and end-to-end connectivity across a layered switched network.
      
### Topology:
- Router
- Switch
- IP Phone
- PC/Laptop

### Notes:
Cisco Packet Tracer lab Overview

<p align="center">
  <img src="Screenshot 2025-12-01 221908.png" width="800" />
</p>

<p align="center">
  <img src="Screenshot 2025-12-01 222049.png" width="800" />
</p>
