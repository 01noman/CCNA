## VLAN Trunking Protocol

## Objective

- The main goals of this lab are:

- Implement VLAN segmentation by creating multiple VLANs for different departments (Sales, IT, HR, Phone, Management, Marketing, R&D).

- Configure a centralized VLAN management system using the VLAN Trunking Protocol (VTP).

- Set up SW1 as the VTP Server to create and maintain the authoritative VLAN database.

- Configure SW3 and SW5 as VTP Clients so they automatically receive and synchronize VLAN information from the VTP Server.

- Keep SW2 in Transparent mode to practice how VTP-transparent devices operate while still allowing VLAN forwarding.

- Configure trunk links between all switches to ensure VLAN advertisements can propagate across the network.

- Assign a VTP domain (nomanisp.net) so all switches belong to the same administrative broadcasting group.

- Secure the domain with a VTP password (cisco) to prevent unauthorized VLAN updates.

- Verify VLAN propagation across all switches using:

- show vtp status

- show vlan

- show interfaces trunk

- Observe configuration revision number changes and understand how VTP uses the revision number to determine the most updated VLAN database.

- Demonstrate automatic VLAN synchronization from server → clients without manually creating VLANs on each switch.

- Understand the behavior of VTP modes:

- Server: Creates and advertises VLANs.

- Client: Receives VLANs, cannot modify.

- Transparent: Forwards VTP frames but does not join or sync.

- Ensure consistent network-wide VLAN configuration in a multi-switch environment.

### Topology:
- Router
- Switch
- PC/Laptop

### Notes:
Cisco Packet Tracer lab Overview

<p align="center">
  <img src="Screenshot 2025-12-04 162721.png" width="800" />
</p>


