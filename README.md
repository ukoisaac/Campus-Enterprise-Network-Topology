## Campus Enterprise Network
📌 Project Overview

This project is a Campus Enterprise Network topology built using Cisco Packet Tracer.
It simulates a real-world network with multiple departments, VLAN segmentation, and a connected branch campus.

🧠 Network Structure
🔹 Main Campus

Core Device: Multilayer Switch (3560)

Connected Buildings:

Building A → Admin, HR

Building B → Finance, Business

Building C → Student Lab, IT Department

🔹 Branch Campus

Separate router and switch

VLANs for:

Staff

Student Lab

🔹 External Network

Cloud connection with Email Server

| VLAN | Department       | Network         |
| ---- | ---------------- | --------------- |
| 10   | Admin            | 192.168.1.0/24  |
| 20   | HR               | 192.168.2.0/24  |
| 30   | Finance          | 192.168.3.0/24  |
| 40   | Business         | 192.168.4.0/24  |
| 50   | E&C              | 192.168.5.0/24  |
| 60   | A&D              | 192.168.6.0/24  |
| 70   | Student Lab      | 192.168.7.0/24  |
| 80   | IT Department    | 192.168.8.0/24  |
| 90   | Staff (Branch)   | 192.168.9.0/24  |
| 100  | Student (Branch) | 192.168.10.0/24 |

##  ⚙️ Key Features

VLAN segmentation

Inter-VLAN routing (Layer 3 switching)

WAN connection (Main ↔ Branch)

Access layer switching (2960 switches)

Server integration (Web, IT, Email)

Hierarchical network design

🖼️ Topology

🚀 How to Run

Download the .pkt file

Open with Cisco Packet Tracer

Test connectivity using ping

Review device configurations

🎯 Objective

To design and implement a scalable campus network demonstrating:

VLAN design

Routing between networks

Enterprise-level topology


<img width="1350" height="599" alt="CAMPUS SS" src="https://github.com/user-attachments/assets/8deae085-7399-447e-ab2a-9f42afec01b0" />


## 👨‍💻 Author
Uko Isaac
Aspiring Network Engineer (CCNA Track)

