# Network Design Project – Cisco Packet Tracer

## Overview
This project demonstrates a multi-floor enterprise network designed and implemented in **Cisco Packet Tracer**.  
The setup uses **OSPF (Open Shortest Path First)** as the dynamic routing protocol and supports **Inter-VLAN routing** for communication between departments.  

## Features
- **Dynamic Routing with OSPF**
  - Configured OSPF process to share routes between core routers and multilayer switches.
  - All devices are part of **Area 0 (backbone)**.

- **Inter-VLAN Routing**
  - Multiple VLANs created for different departments and floors.
  - VLANs assigned IP subnets from the 172.16.x.x range (and 176.16.x.x for ICT).
  - Inter-VLAN communication enabled via multilayer switches.

- **Departmental VLANs**
  - **VLAN 10** – Sales & Marketing (`172.16.1.0/25`)
  - **VLAN 20** – HR & Logistics (`172.16.1.128/25`)
  - **VLAN 30** – Finance (`172.16.2.0/25`)
  - **VLAN 40** – Admin & PR (`172.16.2.128/25`)
  - **VLAN 50** – ICT (`176.16.3.0/25`)
  - **VLAN 60** – Server Room (`172.16.3.128/28`)

- **Servers**
  - DHCP Server (`172.16.3.130`)
  - DNS Server (`172.16.3.131`)
  - Email Server (`172.16.3.133`)

- **Connectivity**
  - End devices (PCs, laptops, tablets, printers) assigned to their respective VLANs.
  - Wireless Access Points provided in each department for wireless clients.
  - Redundant links between core routers and ISPs for reliability.

## Key Technologies
- Cisco Routers & Multilayer Switches  
- OSPF Dynamic Routing  
- VLANs & Inter-VLAN Routing  
- DHCP, DNS, Email Servers  
- Redundant ISP Connectivity  
