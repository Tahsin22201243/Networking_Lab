
# 🌐 Dynamic Routing Using RIP Version 2

### 📘 Project Overview
This project demonstrates an **inter-departmental agriculture network topology** where multiple divisions are interconnected through routers, switches, and servers.  
Dynamic routing is implemented using **RIP Version 2 (Routing Information Protocol)** to automate route learning and updates across the entire network.

---

## 🏢 Departmental Network Structure

| Department | Division Name | Abbreviation |
|-------------|----------------|---------------|
| Soil Research Division | Computer Science & Engineering | SRD |
| Crop Management Division | Electrical & Electronics Engineering | CMD |
| Irrigation & Water Resources Division | Pharmacy | IWRD |
| Fertilizer Distribution Division | Civil Engineering | FDD |
| Agricultural Data & Analytics Division | Business Administration | ADAD |

All divisions are connected to a **Central Server Zone** via routers using serial DTE/DCE connections.

---

## 💾 Server Zone Configuration

| Server Name | Function |
|--------------|-----------|
| AgriData Server | Centralized agriculture data storage |
| WeatherInfo Server | Real-time weather updates |
| SoilAnalysis Server | Soil testing and analysis |
| CropMonitoring Server | Crop health monitoring |
| FarmerPortal Server | Farmer information portal |
| FertilizerControl Server | Fertilizer distribution management |
| IrrigationControl Server | Irrigation system control |
| YieldPrediction Server | Predictive analytics for crop yield |
| DNS Server | Domain Name System for network resolution |

**Total Servers:** 8 + 1 DNS

---

## 🖧 Network Design Approach

- **Routers:** 9 interconnected routers  
- **Switches:** One per department  
- **Cabling:**
  - Router ↔ Router — Serial DTE/DCE
  - Router ↔ Switch — Gigabit Ethernet
  - Switch ↔ Server/PC — Fast Ethernet
- **Routing Protocol:** RIP Version 2 (Dynamic Routing)
- **IP Addressing:** VLSM (Variable Length Subnet Masking) for efficient subnet utilization

### 🔧 Configuration & Testing
1. Setup routers, switches, and servers in Cisco Packet Tracer.
2. Configure each router with RIP v2 using CLI commands.
3. Apply VLSM-based IP addressing.
4. Verify connectivity using:
   - `show ip interface brief`
   - `ping`
   - Web browser to access servers.

---

## ⚙️ Implementation Steps

1. **Network Planning & IP Design**
2. **Hardware & Logical Setup**
3. **RIP v2 Configuration**
4. **Connectivity Testing**
5. **Validation with Browser and CLI**

---

## 🚧 Version 1 Challenges
- Establishing proper **DTE connection** between Router 1 and Router 7.  
- Correcting **VLSM-based IP calculations**.  
- Configuring **routing tables** and verifying serial interfaces.  
- Using `show ip interface brief` and `ping` for troubleshooting.

---

## ✅ Why Version 2 Was Not Needed
After resolving all configuration and connectivity issues in **Version 1**, the network became **fully operational** and optimized.  
Thus, **RIP Version 2 implementation met all project goals**, making additional revisions unnecessary.

---

## 🎯 Key Learnings
- Designing multi-departmental routed networks  
- Implementing dynamic routing using **RIP v2**  
- Applying **VLSM subnetting** for IP efficiency  
- Verifying network connectivity using CLI tools  
- Integrating **DNS and multiple servers** in a routed environment  

---
# UAP_Networking
The CISCO RIP,VLSM,CONFIG,ID addressing and other topics will be available

video Links: 1. https://photos.app.goo.gl/ck2QmtBc6GJrshxV9
             2. https://photos.app.goo.gl/gAJfuPSLNJz2P8Rk7
             3. https://photos.app.goo.gl/RQyASnrWtCAg6jEg6
             4. https://photos.app.goo.gl/jwkcj4t3afHXrAJy7

Notes by Rashik Rahman Sir (Networking):  https://github.com/RashikRahman/3.2_Notes/tree/master/CSE_320_Computer%20Networks%20Lab
## 🖼️ Project Snapshots
---

### 📷 Group 1
| | | |
|---|---|---|
| ![Step 1](Network Final/RIP Photos/Screenshot (2).png) | ![Step 2](Network Final/RIP Photos/Screenshot (3).png) | ![Step 3](Network Final/RIP Photos/Screenshot (4).png) |

### 📷 Group 2
| | | |
|---|---|---|
| ![Router Setup](Network Final/RIP Photos/Screenshot (5).png) | ![Switch Connection](Network Final/RIP Photos/Screenshot (6).png) | ![Server Zone](Network Final/RIP Photos/Screenshot (7).png) |

### 📷 Group 3
| | | |
|---|---|---|
| ![IP Design](Network Final/RIP Photos/Screenshot (8).png) | ![RIP Configuration](Network Final/RIP Photos/Screenshot (9).png) | ![Ping Test](Network Final/RIP Photos/Screenshot (10.png) |

### 📷 Group 4
| | | | |
|---|---|---|---|
| ![Browser Access](Network Final/RIP Photos/Screenshot (11).png) | ![DNS Server](Network Final/RIP Photos/Screenshot (12).png) | ![Full Topology](Network Final/RIP Photos/Screenshot (13).png) | ![Final Output](Network Final/RIP Photos/Screenshot (14).png) |

*(Add your 16 images to a folder named `images/` inside your repo and rename them accordingly.)*

---

## 🧑‍💻 Tools & Technologies
- **Cisco Packet Tracer**
- **RIP v2 Protocol**
- **VLSM Subnetting**
- **Command Line Interface (CLI)**
- **Networking Devices: Router, Switch, Server, PCs**

---

## 🏁 Conclusion
This project successfully implemented **Dynamic Routing using RIP Version 2** across multiple departmental networks.  
It enhanced understanding of IP planning, router configuration, and server integration for a scalable network system.

---

### 👨‍💻 Author
**Tahsin Sheikh**  
Department of Computer Science & Engineering  
University of Asia Pacific

---

### 🏷️ License
This project is licensed under the **MIT License** — feel free to use, modify, and improve it.

---


