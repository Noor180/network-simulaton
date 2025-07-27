# network-simulaton
A Cisco Packet Tracer simulation file demonstrating basic network configuration, including routing, IP addressing, and device connectivity.
# Cisco Packet Tracer Network Simulation

This repository contains a network simulation created using **Cisco Packet Tracer**. The simulation demonstrates a basic routed network with two LANs, switches, and a central router, designed for educational and practice purposes.

## 🖥️ Topology Overview

The simulated network consists of the following devices:

- 4 PCs (PC0, PC1, PC2, PC3)
- 2 Switches (SW1, SW2)
- 1 Router

### 🔗 Connection Layout

- **PC0** and **PC1** are connected to **Switch 1 (SW1)**.
- **PC2** and **PC3** are connected to **Switch 2 (SW2)**.
- **SW1** is connected to the router's **GigabitEthernet0/0** interface.
- **SW2** is connected to the router's **GigabitEthernet0/1** interface.

## 📁 File Included

- `network.pkt` — The Cisco Packet Tracer project file containing the complete network setup.

## 🔁 How the Network Works

- **Switches** connect PCs within the same LAN and forward frames based on MAC addresses.
- **The router** connects both LANs and routes packets between them.
- PCs from **different subnets communicate** through the router.
- Proper IP addressing and default gateways enable end-to-end connectivity.

## 🚀 Getting Started

1. Download and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).
2. Clone or download this repository.
3. Open the `network.pkt` file in Packet Tracer.
