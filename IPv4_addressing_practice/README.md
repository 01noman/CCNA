
## Basic Router Configuration

### Objectives:
- Set Router and switches hostname as R1 and sw1 and sw2
- Set enable secrets "NetworkHacks"
- Create a username "noman" with screts "123"
- Set line console password as "123". Password stored as encrypted in config file.
- Configured IP address as per below plan
    - PC1: 1st useable IP
    - PC2: 11th IP
    - PC3: 100th useabale IP
    - use last useable IP as default gateway and 8.8.8.8 as DNS server
    - PC4-PC6: Will get IP from DHCP server
- Configured a DHCP server at R1 as per below parameters:
    - Pool name: LAN-2
    - DNS server: 1.1.1.1
    - Default router: 1st useable IP
    - Excludd 1st 100 IP's from the DHCP pool
      
### Topology:
- Router
- Switch
- PC/Laptop

### Notes:
Cisco Packet Tracer lab Overview

<p align="center">
  <img src="Screenshot 2025-11-27 120535.png" width="800" />
</p>
