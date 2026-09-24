# Enterprise VLAN Network

Small enterprise network lab created in Cisco Packet Tracer.

## Overview

This project demonstrates VLAN segmentation using a Cisco Catalyst 2960 switch.

Departments:

- VLAN 10 — IT Department
- VLAN 20 — Accounting Department

Devices within the same VLAN can communicate with each other, while different VLANs are isolated.

## Network

- Cisco Catalyst 2960 Switch
- 4 PCs
- VLAN-based network segmentation

## IP Addressing

| Device | VLAN | IP Address | Subnet Mask |
|--------|------|------------|-------------|
| PC1 | 10 | 192.168.10.10 | 255.255.255.0 |
| PC2 | 10 | 192.168.10.20 | 255.255.255.0 |
| PC3 | 20 | 192.168.20.10 | 255.255.255.0 |
| PC4 | 20 | 192.168.20.20 | 255.255.255.0 |

## VLAN Configuration

Created VLANs:

VLAN 10 - IT
VLAN 20 - ACCOUNTING

Configured switch access ports:

Fa0/1 - Fa0/2 → VLAN 10 (IT)
Fa0/3 - Fa0/4 → VLAN 20 (ACCOUNTING)


## Verification

Commands used:
show vlan brief
ping


Results:

- Same VLAN communication: Successful
- Inter-VLAN communication: Blocked

## Skills

- Cisco IOS
- VLAN Configuration
- Switch Port Configuration
- IPv4 Addressing
- Network Troubleshooting

## Tools

- Cisco Packet Tracer
- Cisco Catalyst 2960
