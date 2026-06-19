# Enterprise Campus Network Architecture (Three-Tier) – Cisco Packet Tracer

## Project Overview

This project demonstrates the design, configuration, and validation of a production-style three-tier enterprise campus network using Cisco Packet Tracer.

The network was built to simulate a real-world enterprise environment with redundancy, scalability, secure management, dynamic routing, wireless infrastructure, and multiple network services. It incorporates best practices for Layer 2 switching, Layer 3 routing, high availability, IPv4/IPv6 deployment, and security hardening.



## Network Topology

The project consists of:

* Dual Internet connections for redundancy
* One edge router (R1)
* Two Core Switches
* Two Distribution Switches for each office
* Multiple Access Switches
* Wireless LAN Controller (WLC)
* Lightweight Access Points (LWAPs)
* End-user PCs
* IP Phones
* Server infrastructure
* Dedicated management network

A complete topology diagram is available in the `topology/` folder.



## Key Technologies Implemented

### Layer 2

* VLAN segmentation
* IEEE 802.1Q trunking
* VTP
* EtherChannel (PAgP and LACP)
* Rapid PVST+
* PortFast
* BPDU Guard

### Layer 3

* Inter-VLAN routing
* Layer 3 EtherChannel
* HSRPv2 gateway redundancy
* Static routing
* OSPF dynamic routing

### Network Services

* DHCP
* DHCP Relay
* DNS
* NTP
* SNMP
* Syslog
* FTP
* SSH
* Static NAT
* Dynamic PAT

### Security

* Extended ACLs
* Port Security
* DHCP Snooping
* Dynamic ARP Inspection (DAI)
* SSH-only remote management

### Wireless

* Wireless LAN Controller configuration
* Lightweight Access Point integration
* WPA2-PSK secured wireless network

### IPv6

* Dual-stack deployment
* IPv6 addressing
* IPv6 static routing

---

##  High Availability Features

* Dual Core Switch architecture
* Redundant Distribution layer
* HSRP default gateway redundancy
* Layer 2 and Layer 3 EtherChannels
* STP root bridge optimization
* Dual ISP connectivity
* Floating static routes for failover



##  Repository Structure

```text
docs/
packet-tracer/
screenshots/
topology/
README.md
LICENSE
```



##  Verification

The `screenshots/` folder contains verification outputs demonstrating successful implementation of:

* VLAN configuration
* Interface status
* EtherChannel
* Trunk links
* HSRP
* OSPF neighbors and routes
* Routing table
* DHCP bindings
* NAT translations
* IPv6 configuration
* Port Security
* DHCP Snooping
* Dynamic ARP Inspection
* SSH access
* Wireless LAN Controller configuration
* Wi-Fi security



##  Skills Demonstrated

* Enterprise network design
* Switching and VLAN implementation
* Dynamic routing with OSPF
* Gateway redundancy with HSRP
* EtherChannel configuration
* Network Address Translation (NAT/PAT)
* IPv4 and IPv6 networking
* Wireless LAN deployment
* Infrastructure security
* Network troubleshooting and validation

