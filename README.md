# 🏨 Hotel Network Project (Cisco Packet Tracer)

## 📌 Introduction
This project demonstrates the design and implementation of a secure and scalable network for **Vic Modern Hotel** using Cisco Packet Tracer.  
The hotel consists of **three floors**, and each department is assigned to a unique VLAN to ensure proper segmentation, security, and traffic management.  
Routers are configured with **OSPF** for inter-floor communication, while DHCP provides dynamic IP addressing.  
Security features such as **SSH for remote login** and **port security** are also implemented.

---

## 🗂️ Network Overview
- **Floors:** 3  
- **Departments:** 8 (Reception, Store, Logistics, Finance, HR, Sales, Admin, IT)  
- **Core Devices:** 3 Routers, 3 Switches, Access Points, Printers, PCs, Test-PC  
- **Routing Protocol:** OSPF  
- **Services:** DHCP, SSH, Port Security, WLAN  

---

## 🖧 VLAN & IP Addressing Table

| Floor       | Department | VLAN ID | Network Address   |
|-------------|------------|---------|------------------|
| **1st**     | Reception  | 80      | 192.168.8.0/24   |
|             | Store      | 70      | 192.168.7.0/24   |
|             | Logistics  | 60      | 192.168.6.0/24   |
| **2nd**     | Finance    | 50      | 192.168.5.0/24   |
|             | HR         | 40      | 192.168.4.0/24   |
|             | Sales      | 30      | 192.168.3.0/24   |
| **3rd**     | Admin      | 20      | 192.168.2.0/24   |
|             | IT         | 10      | 192.168.1.0/24   |

---

## ⚙️ Implemented Technologies
- **Hierarchical Network Design**
- **VLANs** for departmental segmentation  
- **Inter-VLAN Routing** using Router-on-a-Stick  
- **OSPF** as the dynamic routing protocol  
- **DHCP** (Router as DHCP server)  
- **SSH** for secure remote access  
- **Port Security** on IT switch (`fa0/1` restricted to Test-PC)  
- **Wireless LAN (WLAN)** for laptops and mobile devices  
- **Printers** assigned per department  

---

## 🧪 Testing & Verification
- ✅ Devices within each VLAN obtained IPs dynamically from DHCP  
- ✅ Inter-VLAN communication verified via ping  
- ✅ OSPF successfully advertised networks between routers  
- ✅ SSH remote login tested from **Test-PC**  
- ✅ Port security tested with sticky MAC (violation mode: shutdown)  
- ✅ WLAN devices connected successfully to APs  

---

## 📂 Files Included
- `hotel_network.pkt` → Cisco Packet Tracer topology  
- `docs/hotel_network_project.pdf` → Detailed documentation report  

---

## 🏁 Conclusion
The hotel network was successfully designed and implemented using Cisco Packet Tracer.  
The solution ensures:  
- Departmental isolation through VLANs  
- Secure and scalable inter-floor routing using OSPF  
- Dynamic addressing via DHCP  
- Enhanced security with SSH and port security  
- Wireless connectivity for mobile devices  

This project demonstrates professional-level networking skills in **LAN/WAN design, VLAN segmentation, routing, security, and wireless integration**.

