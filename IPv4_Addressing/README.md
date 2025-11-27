
## IPv4 Addressing Using DHCP Server

## 🎯 Objective

The objective of this lab is to configure and enable the GigabitEthernet interfaces on a Cisco router and assign valid IPv4 addresses to establish basic Layer 3 network communication.

This lab focuses on:

- Entering privileged and global configuration modes correctly  
- Activating interfaces using the `no shutdown` command  
- Assigning IPv4 addresses to:
  - GigabitEthernet0/0 → 192.168.0.1 /24  
  - GigabitEthernet0/1 → 192.168.1.1 /24  
- Observing interface state changes from down to up  
- Identifying and correcting IOS command syntax errors  
- Verifying configuration using `show running-config`

The configuration prepares the router to route traffic between two separate networks:
- **192.168.0.0/24**
- **192.168.1.0/24**

This exercise strengthens understanding of basic router interface configuration and command-line troubleshooting in Cisco IOS.


### Topology:
- Router
- Switch
- DHCP Server
- PC/Laptop

### Notes:
Cisco Packet Tracer lab Overview

<p align="center">
  <img src="Screenshot 2025-11-27 004606.png" width="800" />
</p>
