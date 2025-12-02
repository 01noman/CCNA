## VLAN

## TASK

1) Set Router and Switches hostname as R1 and SW1 and SW2.
2) Set enable secrets as "CCNA" in all cisco devices.
3) Configured VLAN in the switches as per diagram VLAN names should be as per LAN name.
4) Set switchport modes accordingly and assign corresponding VLANs.
5) For each LAN set a gateway address at R1. Might need to create subinterface.
   Here uses the 1st useable address as gateway address except for IT-LAN and DHCP server.
6) Add description to router each connected interface (such "To-Sales-LAN)
7) Each host and server machines are configured with proper IP addressing. Sales-LAN hosts will get IP information dynamically from DHCP Server.
   HR-LAN and Phone-LAN will get IP dynamically from DHCP server at R1.
8) Configure DHCP servers at R1, use DNS as 8.8.8.8  pool names should be per LAN names. Exclude 1st 11th address from each LAN pool
9) Check all the hots are configured with proper IP information and reachable to each other


### Topology:
- Router
- Switch
- DHCP Server
- IP Phone
- PC/Laptop

### Notes:
Cisco Packet Tracer lab Overview

<p align="center">
  <img src="Screenshot 2025-12-03 014041.png" width="800" />
</p>

