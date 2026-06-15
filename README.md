**Computer Networks - Router Configuration and Routing Protocols Assignment**

This repository contains the practical deliverables for the Computer Networks (CN module assignment. The project focuses on basic router hardening, static routing configuration, and dynamic routing using RIPv2 and EIGRP protocols inside Cisco Packet Tracer.

---

## 👤 Student Details
- Student Name: K.P.R.Kapuruge
- Student ID: 39306
- Module Computer Networks (CN)

---

## 📁 Repository Structure

This repository includes the following three Cisco Packet Tracer (`.pkt`) files, corresponding to each task required in the assignment guidelines:

1. Task2_StaticRouting.pkt
   - Contains a triangular network topology connecting three institutional networks (Computing Router, Business Router, and Science Router).
   - Fully configured using manual **Static Routes** (`ip route`) to achieve 100% end-to-end connectivity.
   
2. Task3_RIP.pkt
   - Features a linear network topology connecting Kandy, Colombo, and Galle NSBM branches.
   - Dynamic routing is implemented using RIPv2 (Routing Information Protocol Version 2) with classless routing and auto-summarization disabled (`no auto-summary`).

3. Task3_EIGRP.pkt
   - Features the same linear network topology as Task 3 Part A, but with RIPv2 removed completely.
   - Dynamic routing is re-implemented using Cisco's EIGRP (Enhanced Interior Gateway Routing Protocol with Autonomous System (AS) number `10` for faster convergence and optimal path selection.

---

## 🛠️ Summary of Implemented Tasks

### Task 1: Basic Router Hardening
- Router hostname updated to standard university format: `KandyNSBM_39306`.
- Secured console line connection access with the password `NSBM` and enabled proper authentication login.

### Task 2: Static Routing Implementation
- Assigned distinct subnet ranges (`192.168.1.0/24`, `192.168.2.0/24`, `192.168.3.0/24`) to local LAN networks.
- Interconnected routers via WAN point-to-point subnets (`12.0.0.0/30`, `11.0.0.0/30`, `10.0.0.0/30`).
- Configured manual static routing tables across all interfaces.

### Task 3: Dynamic Routing Protocols (RIPv2 & EIGRP)
- Configured dynamic route advertising over `172.16.0.0/16` and `173.16.0.0/16` subnets.
- Verified neighbor relationships, analyzed structural differences in routing tables, and validated full ICMP connectivity between local host machines via command prompt ping tests.

---

## 🚀 How to Run the Files
1. Download and install Cisco Packet Tracer (version 8.0 or higher recommended).
2. Clone or download this repository to your local computer.
3. Open any of the `.pkt` files to inspect CLI configurations or run interactive simulation modes to test cross-network pings.
