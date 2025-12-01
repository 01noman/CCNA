

## DHCP Relay Agent

## 🎯 Objective

The purpose of this lab is to demonstrate how DHCP services can be extended across multiple networks using a DHCP Relay Agent. Since DHCP normally operates only within the same broadcast domain, routers must relay DHCP requests when clients are located in different VLANs or subnets.

This project shows how to:

- Configure a router to forward DHCP broadcasts using the ip helper-address command.

- Enable DHCP clients in separate LANs/VLANs to receive IP addresses from a central DHCP server.

- Create and manage separate subnets/SVI interfaces for Sales, IT, and Management networks.

- Verify DHCP bindings and relay operation using Packet Tracer.

- Understand how DHCP relay allows centralized IP management across routed networks.

The topology includes multiple VLANs connected through a router, where only one subnet hosts the DHCP server. All other subnets rely on DHCP relay to obtain IP configuration automatically.

### Topology:
- Router
- Switch
- DHCP Server
- PC/Laptop

### Notes:
Cisco Packet Tracer lab Overview

<p align="center">
  <img src="Screenshot 2025-12-01 124310.png" width="800" />
</p>
