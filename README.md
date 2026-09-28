# Enterprise Multi-Router Network with DHCP & Routing

## 📋 Project Overview
This repository contains an advanced Cisco Packet Tracer network implementation featuring multiple interconnected Cisco 2911 routers, switch-based local access networks, and centralized IP configuration management.

---

## 🏗️ Network Topology & Design
* **Topology Type:** Multi-Router Enterprise Network
* **Core Devices:** 
  * **Routers:** 4x Cisco 2911 Routers (interlinked via GigabitEthernet interfaces)
  * **Switches:** Cisco 2960 Access Switches deployed across multiple subnets
  * **End Devices:** Multiple PCs configured across departments
* **Subnet Architecture:** Includes segmented networks such as `50.0.0.0`, `60.0.0.0`, `70.0.0.0`, and `192.168.10.0`.

---

## ⚙️ Implemented Configurations
* **Dynamic / Static Routing:** Configured pathways for cross-network communication between separate router domains.
* **DHCP Services & Helper Address:** Configured `ip helper-address` on router interfaces to forward DHCP broadcast requests across network segments to a central server.
* **IP Exclusion Ranges:** Implemented DHCP address pooling with specific exclusion ranges to avoid IP conflicts.

---

## 📂 Repository Structure
```text
├── topology/
│   └── network_design.pkt         # Cisco Packet Tracer topology file
├── screenshots/
│   ├── multi_router_layout.png    # Overall multi-router network layout
│   └── ping_success.png           # End-to-end ping verification
└── README.md
