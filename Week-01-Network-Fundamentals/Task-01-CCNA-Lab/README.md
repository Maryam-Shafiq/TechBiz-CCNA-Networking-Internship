# Task 01 – Build Your CCNA Lab + How Networks Actually Work

## Overview
This project involves building and configuring a basic network topology using Cisco Packet Tracer as part of the TechBiz CCNA Networking Internship.

The lab demonstrates the fundamentals of networking, IPv4 addressing, router and switch configuration, and communication between different networks.

## Network Topology

**Devices used:**
- 2 × Cisco 2911 Routers
- 2 × Cisco 2960 Switches
- 4 × PCs

## Network Addressing

| Network | Address | Subnet Mask |
|---|---|---|
| LAN 1 | 192.168.10.0/24 | 255.255.255.0 |
| Router Link | 10.0.0.0/30 | 255.255.255.252 |
| LAN 2 | 192.168.20.0/24 | 255.255.255.0 |

## Configurations Implemented

- Configured IPv4 addresses on routers and PCs.
- Configured switch management IP addresses.
- Enabled router interfaces using the Cisco IOS CLI.
- Configured static routes between the two LANs.
- Verified routing tables and interface status.

## Connectivity Testing

Connectivity was tested using ICMP ping commands.

All four PCs successfully communicated with one another across the two networks.

## Key Concepts Learned

- Network devices and their functions.
- IPv4 addressing and subnet masks.
- Default gateways.
- Router interfaces and Cisco IOS commands.
- Static routing.
- Packet forwarding between different networks.

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

## Project Files

- Packet Tracer topology: `task1-topology.pkt`
- Lab report: `Task1-Lab-Report.pdf`
- Screenshots: Available in the Screenshots folder.

---

**Internship:** TechBiz – CCNA Networking  
**Week:** 1  
**Task:** 1
