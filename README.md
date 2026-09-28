# Enterprise Multi-Router Network with DHCP & Routing

## 📋 Project Overview
This repository contains an advanced Cisco Packet Tracer network implementation featuring multiple interconnected Cisco 2911 routers, switch-based local access networks, and centralized IP configuration management[cite: 6, 8, 12].

---

## 🏗️ Network Topology & Design
* **Topology Type:** Multi-Router Enterprise Network[cite: 6, 8]
* **Core Devices:** 
  * **Routers:** Cisco 2911 Routers interlinked via GigabitEthernet interfaces[cite: 6, 8]
  * **Switches:** Cisco 2960 Access Switches deployed across multiple subnets[cite: 6, 8]
  * **End Devices:** Multiple PCs configured across departments[cite: 6, 8]
* **Subnet Architecture:** Includes segmented networks such as `50.0.0.0`, `60.0.0.0`, `70.0.0.0`, and `192.168.10.0`[cite: 6, 8].

---

## ⚙️ Implemented Configurations
* **Dynamic / Static Routing:** Configured pathways for cross-network communication between separate router domains[cite: 6, 8].
* **DHCP Services & Helper Address:** Configured `ip helper-address` on router interfaces to forward DHCP broadcast requests across network segments to a central server[cite: 6].
* **IP Exclusion Ranges:** Implemented DHCP address pooling with specific exclusion ranges to avoid IP conflicts[cite: 6].

---

## 📂 Repository Structure
```text
├── DHCP.pkt                 # Cisco Packet Tracer topology file[cite: 12]
├── DHCP Routing.docx        # Detailed lab report and documentation
└── README.md                # Project documentation
