# VLAN and VTP Network Segmentation Lab

## Overview
This project demonstrates a Cisco Packet Tracer lab using VLANs, VTP, and trunk ports to segment network traffic and improve security.

## Technologies Used
- Cisco Packet Tracer
- Cisco IOS
- VLANs
- VTP
- Trunking
- Layer 2 Switching

## Lab Design
The network includes three switches:
- VTP Server
- VTP Transparent Switch
- VTP Client

VLANs configured:
- VLAN 10: Users
- VLAN 20: Servers

## Configuration
Ports Fa0/1 to Fa0/10 were assigned to VLAN 10.
Ports Fa0/11 to Fa0/20 were assigned to VLAN 20.
Trunk ports were configured between switches.

## Skills Demonstrated
- VLAN creation
- VTP server, client, and transparent modes
- Trunk port configuration
- Network segmentation
- Cisco IOS commands
- Basic network security concepts

## Verification
The configuration was verified using:
- show vlan brief
- show interfaces trunk
- ping tests

## Conclusion
This lab helped me understand how VLANs and VTP are used to manage and secure network traffic in enterprise environments.
