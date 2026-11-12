# Task 02 – IPv4 Addressing, Binary & VLSM Subnetting

This task was completed as part of the **TechBiz CCNA Networking Internship**.

The objective was to practise IPv4 binary conversion, understand subnetting concepts, perform VLSM subnet allocation and implement the resulting addressing plan in Cisco Packet Tracer.

## Overview

The original `192.168.10.0/24` network was divided into five subnets based on the required host counts.

A practical network topology was then built and configured using Cisco Packet Tracer, with static routing to enable communication between different LANs.

## VLSM Address Allocation

| Host Requirement | Network Address | Prefix | Usable Host Range | Broadcast |
|---|---|---|---|---|
| 50 hosts | 192.168.10.0 | /26 | .1 – .62 | .63 |
| 25 hosts | 192.168.10.64 | /27 | .65 – .94 | .95 |
| 12 hosts | 192.168.10.96 | /28 | .97 – .110 | .111 |
| 2 hosts | 192.168.10.112 | /30 | .113 – .114 | .115 |
| 2 hosts | 192.168.10.116 | /30 | .117 – .118 | .119 |

All five subnets were allocated without overlapping address ranges.

## Network Topology

**Devices used:**
- 3 × Cisco 2911 Routers
- 3 × Cisco 2960 Switches
- 4 × PCs

The topology consists of three separate LANs connected through three routers. The two `/30` subnets are used for point-to-point router connections.

## Configurations Implemented

- Performed decimal-to-binary and binary-to-decimal conversions.
- Calculated network addresses, broadcast addresses and usable host ranges.
- Designed a VLSM addressing plan for five subnets.
- Configured IPv4 addresses and subnet masks on routers and PCs.
- Configured switch management IP addresses.
- Enabled router interfaces using Cisco IOS CLI.
- Configured static routes between the three LANs.
- Verified interface status and routing tables.

## Connectivity Testing

Connectivity was tested using ICMP ping commands.

- Verified PC-to-gateway connectivity.
- Tested communication between PCs within different LANs.
- Verified end-to-end communication across all three routers.

All four PCs successfully communicated with one another.

## Key Concepts Learned

- IPv4 addressing and binary conversion.
- Network addresses and broadcast addresses.
- Subnet masks and CIDR notation.
- Variable Length Subnet Masking (VLSM).
- Efficient IP address allocation.
- Default gateways.
- Static routing.
- Router interfaces and Cisco IOS CLI.
- Network connectivity verification.

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

## Project Files

- `Task2-VLSM-Lab.pkt` – Configured Packet Tracer network topology.
- `Task2-VLSM-Subnetting-Report.pdf` – Detailed task report.
- `Screenshots/` – Lab topology, router configurations, routing tables and connectivity test evidence.

---

**Internship:** TechBiz – CCNA Networking  
**Week:** 1  
**Task:** 2
