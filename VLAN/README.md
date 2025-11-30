

## VLAN

### Objectives:
The objective of this lab is to create and verify multiple VLANs on a Cisco switch, assign specific ports to each VLAN, and connect end devices according to their department networks. This lab demonstrates how access ports handle untagged traffic, how VLANs segment broadcast domains, and how to verify VLAN configuration using IOS commands.

## VLAN Design

| VLAN Name      | VLAN ID | Ports Assigned       | Subnet         |
| -------------- | ------- | -------------------- | -------------- |
| Sales LAN      | 10      | Fa0/3, Fa0/4, Gi0/2  | 192.168.0.0/24 |
| IT LAN         | 20      | Fa0/1, Fa0/2, Gi0/1  | 192.168.1.0/24 |
| Management LAN | 30      | Fa0/5, Fa0/6, Fa0/24 | 192.168.2.0/24 |

### Topology:
- Router
- Switch
- PC/Laptop

### Notes:
Cisco Packet Tracer lab Overview

<p align="center">
  <img src="Screenshot 2025-11-30 172034.png" width="800" />
</p>
