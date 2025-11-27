
## IPv4 Addressing configure DHCP services on a Cisco router

## 🎯 Objective

The objective of this lab is to configure and manage DHCP services on a Cisco router for two separate LAN networks, enabling automatic IP address assignment to client devices while reserving specific address ranges for static configuration.

This lab demonstrates:

- Creating DHCP pools for two networks:
  - **LAN-1 → 192.168.0.0 /24**
  - **LAN-2 → 192.168.1.0 /24**
- Defining default gateways for each LAN:
  - LAN-1 → 192.168.0.1  
  - LAN-2 → 192.168.1.1  
- Configuring DNS server settings using **8.8.8.8**
- Excluding IP address ranges from DHCP assignment to prevent conflicts with static devices:
  - LAN-1 excluded range: 192.168.0.2 – 192.168.0.99  
  - LAN-2 excluded ranges:
    - 192.168.1.2 – 192.168.1.99  
    - 192.168.1.100 – 192.168.1.150  
- Understanding correct command placement and identifying IOS syntax errors during DHCP configuration

This configuration ensures structured IP address management, controlled allocation, and reliable connectivity across both LAN segments while maintaining reserved address space for infrastructure devices such as routers, servers, and printers.

### Topology:
- Router
- Switch
- PC/Laptop

### Notes:
Cisco Packet Tracer lab Overview

<p align="center">
  <img src="Screenshot 2025-11-27 012739.png" width="800" />
</p>
