# 🍕 Desi Pizza - Smart Network Design Project

![Network Project](https://img.shields.io/badge/Project-Networking-blue)
![Cisco](https://img.shields.io/badge/Tool-Cisco%20Packet%20Tracer-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Project Overview

A complete **network infrastructure design** for a small pizza shop "**Desi Pizza**" using **Cisco Packet Tracer**. This project demonstrates practical application of networking concepts in a real-world business scenario.

---

## 🏪 Business Details

| Detail | Information |
|--------|-------------|
| **Shop Name** | Desi Pizza |
| **Address** | Shop No. 24A, College Road Lane |
| **City** | Ghatshila, Jharkhand |
| **PIN Code** | 832303 |
| **Phone** | +91 9065218915 |
| **WhatsApp** | +91 9065218915 |

---

## 🖥️ Network Topology
    📶 [Customer Wi-Fi]
          │
🌐 ──[DESI-PIZZA-ROUTER]── Gateway + DHCP
          │
      [PIZZA-SWITCH]
     /   |   |   \   \
    /    |   |    \   \
[PC1] [PC2] [PC3] [Server] [Printer]
  │     │     │       │        │
---

## 📊 Network Specifications

| Component | Details |
|-----------|---------|
| **Topology** | Star Topology |
| **Network Address** | 192.168.1.0/24 |
| **Subnet Mask** | 255.255.255.0 |
| **Gateway** | 192.168.1.1 |
| **DNS Server** | 192.168.1.100 |
| **Total Devices** | 9 |

---

## 🔧 Devices Used

| # | Device | Model | IP Address | Purpose |
|---|--------|-------|------------|---------|
| 1 | Router | Cisco 2911 | 192.168.1.1 | Gateway, DHCP |
| 2 | Switch | Cisco 2960 | - | Connectivity |
| 3 | Billing PC | PC-PT | 192.168.1.20 | Take Orders |
| 4 | Kitchen PC | PC-PT | 192.168.1.21 | Display Orders |
| 5 | Manager PC | PC-PT | 192.168.1.22 | Management |
| 6 | Web Server | Server-PT | 192.168.1.100 | Website + DNS |
| 7 | Printer | Printer-PT | 192.168.1.50 | Print Bills |
| 8 | Access Point | AP-PT | - | Customer Wi-Fi |
| 9 | Customer Laptop | Laptop-PT | 192.168.1.30 | Customer Use |

---

## ⚡ Features Implemented

- ✅ **DHCP** - Automatic IP assignment
- ✅ **DNS** - Domain name resolution (www.desipizza.com)
- ✅ **Web Server** - Pizza menu website
- ✅ **Star Topology** - Reliable network design
- ✅ **Customer Wi-Fi** - Free internet for customers
- ✅ **Network Printer** - Bill printing

---

## 🌐 Website Features

The project includes a complete website with:

- 🍕 Pizza Menu (7 items with prices)
- 🍟 Sides & Beverages (6 items)
- 🎁 Combo Offers (3 deals)
- 📞 Contact Information
- 📍 Shop Address with PIN code
- 🖧 Network Information Table
- ⭐ Customer Reviews

**Website URL:** `www.desipizza.com`

---

## 💰 Cost Estimation

| Item | Quantity | Cost (₹) |
|------|----------|----------|
| Wi-Fi Router | 1 | 2,500 |
| Network Switch | 1 | 1,500 |
| Desktop PCs | 3 | 75,000 |
| Server PC | 1 | 40,000 |
| Printer | 1 | 3,000 |
| Access Point | 1 | 2,000 |
| Cables & Accessories | - | 3,000 |
| **TOTAL** | | **₹1,27,000** |

---

## 🛠️ Technologies Used

- **Cisco Packet Tracer 8.2** - Network Simulation
- **HTML** - Website Development
- **DHCP Protocol** - IP Assignment
- **DNS Protocol** - Domain Resolution
- **HTTP Protocol** - Web Services

---

## 📸 Screenshots

### Network Topology
![Topology](screenshots/topology.png)

### Website Homepage
![Website](screenshots/website.png)

### Ping Test
![Ping](screenshots/ping-test.png)

---

## 🚀 How to Run

1. Download and install **Cisco Packet Tracer**
2. Download `Desi_Pizza_Network.pkt` file
3. Open the file in Packet Tracer
4. Click on any PC → Desktop → Web Browser
5. Type `www.desipizza.com` and press Enter
6. 🍕 Pizza website will open!

---

## 📝 Project Files

| File | Description |
|------|-------------|
| `Desi_Pizza_Network.pkt` | Packet Tracer project file |
| `index.html` | Website source code |
| `README.md` | Project documentation |
| `/screenshots` | Project screenshots |

---

## 👨‍💻 Developer

**SOUGAT DAS**

- 📍 Ghatshila, Jharkhand, India
- 📞 +91 9065218915
- 🎓 Networking Project 2024-2025

---

## 📄 License

This project is for educational purposes only.

---

## 🙏 Acknowledgements

- Cisco Networking Academy
- College Faculty & Mentors

---

<p align="center">
  <b>⭐ If you found this project helpful, please give it a star! ⭐</b>
</p>

<p align="center">
  Made with ❤️ by Sougat Das
</p>

  
