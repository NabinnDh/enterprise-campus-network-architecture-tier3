# Enterprise Campus Network Architecture

## Overview

This repository contains a complete enterprise campus network built in Cisco Packet Tracer using a three-tier hierarchical design. The project was created as a practical exercise to apply routing, switching, redundancy, security, and infrastructure services in a single integrated environment rather than as isolated lab tasks.

The topology connects two office locations through redundant core infrastructure and dual Internet links while providing reliable connectivity for wired clients, wireless users, IP phones, and internal servers. The design emphasizes availability, scalability, and maintainability, following concepts commonly used in enterprise networks.

## Network Design

The environment is organized into Core, Distribution, and Access layers to separate responsibilities and simplify management.

Key components include:

* Redundant Internet connectivity through two ISPs
* An edge router providing WAN access and NAT services
* Dual Core Switches interconnected with a Layer 3 EtherChannel
* Distribution switches for Office A and Office B
* Multiple Access Switches serving end devices
* Wireless LAN Controller and Lightweight Access Points
* Centralized server providing network services
* Segregated user, voice, wireless, server, and management VLANs

The complete topology diagram is available in the `topology` directory.

## Implemented Features

This project combines a wide range of enterprise networking technologies into a single working design, including:

* VLAN creation and segmentation
* IEEE 802.1Q trunking
* VTP domain configuration
* Layer 2 EtherChannel using both PAgP and LACP
* Layer 3 EtherChannel between Core Switches
* Inter-VLAN routing
* HSRPv2 for default gateway redundancy
* Rapid PVST+ with root bridge optimization
* OSPF dynamic routing across Layer 3 devices
* Static and floating default routes
* DHCP and DHCP relay
* DNS, NTP, SNMP, and Syslog services
* Secure remote administration using SSH
* Static NAT and dynamic PAT
* IPv4 and IPv6 dual-stack configuration
* Wireless LAN Controller integration with WPA2 security
* Extended ACLs for traffic filtering
* Port Security
* DHCP Snooping
* Dynamic ARP Inspection (DAI)

## Validation

Every major feature was configured and verified through CLI commands and functional testing. The `screenshots` directory contains command outputs and verification images covering:

* Interface status
* VLAN assignments
* EtherChannel operation
* Trunk configuration
* HSRP state
* OSPF neighbors and learned routes
* Routing tables
* DHCP bindings
* NAT translations
* IPv6 interfaces
* Port Security
* DHCP Snooping
* Dynamic ARP Inspection
* SSH connectivity
* Wireless LAN Controller configuration
* Wi-Fi security settings

## Repository Structure

```text
enterprise-campus-network-architecture/
├── docs/
├── packet-tracer/
├── screenshots/
├── topology/
├── README.md
└── LICENSE
```

## Skills Applied

Developing this project required planning and implementing multiple networking disciplines within a single environment, including enterprise switching, dynamic routing, gateway redundancy, infrastructure services, wireless networking, IPv6 deployment, network security, and troubleshooting.

Rather than focusing on individual commands, the objective was to build a cohesive and resilient campus network where all components operate together as a complete system.

## Technologies

* Cisco Packet Tracer
* Cisco IOS
* OSPF
* HSRP
* VLANs
* EtherChannel
* Rapid PVST+
* NAT/PAT
* DHCP
* DNS
* SNMP
* Syslog
* SSH
* IPv6
* Wireless LAN Controller (WLC)
* Port Security
* DHCP Snooping
* Dynamic ARP Inspection


