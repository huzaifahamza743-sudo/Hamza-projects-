<!-- Header / Animated Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00A86B,100:0056A6&height=200&section=header&text=CCNA%20Networking%20Labs&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35" width="100%">
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=00A86B&center=true&vCenter=true&width=600&lines=Building+Networks+%F0%9F%94%8C;Routing+%26+Switching+Mastery+%F0%9F%93%A1;CCNA+In+Progress+%E2%9C%85" alt="Typing Animation">
</p>

<!-- Badges Row -->
<p align="center">
  <img src="https://img.shields.io/badge/CCNA-Student-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" alt="CCNA Student">
  <img src="https://img.shields.io/badge/Networking-Labs-00A86B?style=for-the-badge&logo=cisco&logoColor=white" alt="Networking Labs">
  <img src="https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO?style=for-the-badge&logo=github&color=yellow" alt="GitHub Stars">
  <img src="https://img.shields.io/badge/Markdown-Ready-000000?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=YOUR_USERNAME.YOUR_REPO&title=Visitors&style=for-the-badge&color=00A86B" alt="Visitor Counter">
</p>

## 📖 Table of Contents
- [📌 About the Repository](#-about-the-repository)
- [⚙️ Technologies Used](#️-technologies-used)
- [📡 Networking Topics Covered](#-networking-topics-covered)
- [🖧 Lab Topologies](#-lab-topologies)
- [🎥 Lab Demo Videos](#-lab-demo-videos)
- [🎯 Learning Goals](#-learning-goals)
- [🚀 Future Improvements](#-future-improvements)
- [🤝 Connect With Me](#-connect-with-me)

---

## 📌 About the Repository

> *"Hands-on practice is the bridge between theory and expertise."*

Welcome to my **CCNA Networking Labs** repository! 🧪  
This is where I document my journey through the Cisco Certified Network Associate (CCNA) curriculum. Here you'll find:

- ✅ Real-world topology designs  
- ✅ Step-by-step configuration labs  
- ✅ Troubleshooting scenarios & output examples  
- ✅ Video walkthroughs of key concepts  

**Why this repo?**  
To track my progress, share learning resources, and help fellow CCNA students master networking fundamentals.

---

## ⚙️ Technologies Used

| Category       | Tools / Technologies                           |
|----------------|------------------------------------------------|
| **Simulation** | Cisco Packet Tracer, GNS3, EVE-NG             |
| **Protocols**  | OSPF, VLANs, STP, EtherChannel, HSRP, ACLs, NAT |
| **Languages**  | Cisco IOS CLI, Bash (for automation scripts)  |
| **Versioning** | Git & GitHub                                   |
| **Docs**       | Markdown, Diagrams.net (topology visuals)     |

---

## 📡 Networking Topics Covered

<details>
<summary>📌 Click to expand full topic list</summary>

- **IPv4 & IPv6 Addressing** – Subnetting, VLSM, SLAAC
- **Switching** – VLANs, Trunking (DTP, 802.1Q), VTP, STP, RSTP, EtherChannel
- **Routing** – Static routing, Default routes, OSPFv2, OSPFv3 (multi-area)
- **Network Services** – DHCP, DNS, NAT (Static, Dynamic, PAT), NTP
- **Security** – ACLs (Standard/Extended), Port Security, SSH, DHCP Snooping
- **WAN & Redundancy** – HSRP, GLBP, PPP, GRE Tunnels
- **Network Management** – CDP, LLDP, SNMP, Syslog, NetFlow basics

</details>

---

## 🖧 Lab Topologies

> *Click on any image to expand — all topologies built & configured from scratch.*

### 🔹 Lab 1 — Basic Router & Switch Initialization
![Lab 1 Topology](lab1.png)  
**Description:** Initial device setup, hostnames, banners, password encryption, and console/SSH access.

### 🔹 Lab 2 — VLAN & Trunking Configuration
![Lab 2 Topology](lab2.png)  
**Description:** Multi-switch topology with VLAN 10, 20, 30, trunk links, and inter-VLAN routing using Router-on-a-Stick.

### 🔹 Lab 3 — Static & Default Routing
![Lab 3 Topology](lab3.png)  
**Description:** Three-router topology practicing static routes, default routes, and route backup using floating static.

### 🔹 OSPF Multi-Area Design
![OSPF Topology](ospf-topology.png)  
**Description:** Area 0 backbone with areas 1 & 2, OSPF authentication, and route summarization.

### 🔹 VLAN Security & Access Ports
![VLAN Configuration](vlan-config.png)  
**Description:** Port-security sticky MAC, unused port shutdown, and DHCP snooping for VLAN isolation.

---

## 🎥 Lab Demo Videos

Watch my hands-on configuration walkthroughs (click the links to view the `.mp4` files locally or download).

| Title | Preview | Watch |
|-------|---------|-------|
| **VLAN Configuration & Trunking** | 🎬 Step-by-step VLAN creation, trunk ports, and inter-VLAN routing | [▶ Watch Video](vlan-demo.mp4) |
| **OSPF Single-Area & Multi-Area** | 🎬 OSPF network commands, router IDs, and verification commands | [▶ Watch Video](ospf-demo.mp4) |
| **Routing Lab – Static + Default** | 🎬 Configuring static routes, default routes, and failover testing | [▶ Watch Video](routing-lab.mp4) |

> 💡 **Tip:** Download the videos to watch in high resolution or integrate them into your local video player.

<details>
<summary>📽️ Embedded video player (optional)</summary>

```html
<video src="vlan-demo.mp4" controls width="700"></video>
<video src="ospf-demo.mp4" controls width="700"></video>
<video src="routing-lab.mp4" controls width="700"></video>
