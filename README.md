# 🛜 Public Wi-Fi & Guest Network — Shopping Mall

A Cisco Packet Tracer-based Computer Networks project designed to provide reliable public Wi-Fi access for shopping mall visitors while maintaining organized connectivity for internal mall operations.

## 📌 Project Overview

This project simulates a shopping mall network with separate sections for:

- 🏢 Management
- 🛍️ Shops
- 🍔 Food Court
- 🛡️ Security
- 🌐 Public Guest Wi-Fi
- 🖥️ Central Server
- 🌍 Internet Connectivity

The network uses a centralized Core Switch architecture with dedicated switches for different operational areas. Guest users connect through a dedicated wireless Access Point and receive network configuration dynamically through DHCP.

## 🏗️ Network Topology

```text
                         🌍 Internet
                              |
                         Mall_Router
                              |
                         Core_Switch
          _________________|____________________
         |          |          |        |       |
         |          |          |        |       |
    Management    Shops    FoodCourt  Security Guest
        SW          SW         SW        SW      SW
       /  \          |          |         |       |
    Admin Manager  Shop PC  FoodCourt  Security MallGuest_AP
      PC     PC               PC         PC       |
                                            Guest Devices
````

## ⚙️ Main Components

| Device        | Purpose                      |
| ------------- | ---------------------------- |
| Mall_Router   | Internet and network routing |
| Core_Switch   | Central network connectivity |
| Management_SW | Management devices           |
| Shops_SW      | Shop network                 |
| FoodCourt_SW  | Food court network           |
| Security_SW   | Security network             |
| Guest_SW      | Public Wi-Fi network         |
| Main_Server   | Centralized network services |
| MallGuest_AP  | Guest wireless access        |
| Guest Devices | Public Wi-Fi clients         |

## 🔑 Key Features

* Public Wi-Fi for mall visitors
* DHCP-based dynamic IP addressing
* Separate network areas for different departments
* Centralized switching architecture
* Wired and wireless connectivity
* IP addressing and subnetting
* VLAN-based network segmentation
* Routing configuration
* Network security considerations
* Connectivity testing and troubleshooting
* Scalable network structure

## 👨‍💻 My Contribution

As a team member, I contributed to the design, implementation, configuration, testing, and documentation of the project.

### My responsibilities included:

* Designed and organized the shopping mall network topology
* Configured and connected network devices in Cisco Packet Tracer
* Worked on the Guest Wi-Fi network
* Configured wireless client connectivity
* Worked with DHCP-based IP addressing
* Assisted with IP addressing and subnetting
* Worked on network segmentation and VLAN planning
* Assisted with router and switch configuration
* Performed connectivity testing using Ping and Packet Tracer Simulation Mode
* Identified and troubleshot network connectivity issues
* Prepared and documented the technical report
* Contributed to the final network evaluation and security analysis

## 🧪 Testing

Network connectivity was tested between different network devices and end devices using:

```bash
ping <destination-ip>
```

Cisco Packet Tracer commands such as:

```bash
show ip interface brief
show ip route
show vlan brief
```

were used for network verification and troubleshooting.

## 🔐 Security Considerations

Because this project provides public Wi-Fi, guest users should be treated as untrusted users.

The design considers:

* Guest network isolation
* VLAN segmentation
* Access Control Lists (ACLs)
* Wireless authentication and encryption
* Protection of management and security networks
* Prevention of unauthorized internal access

## 🚀 Future Improvements

Possible future improvements include:

* Captive portal for guest authentication
* Dedicated firewall
* Multiple wireless Access Points
* Wi-Fi 6/6E deployment
* Centralized network monitoring
* Bandwidth management
* Redundant network devices
* Advanced ACL policies
* Intrusion Detection/Prevention

## 🛠️ Technologies Used

* Cisco Packet Tracer
* Cisco Routers
* Cisco Switches
* Wireless Access Point
* DHCP
* IP Networking
* VLAN
* Routing
* TCP/IP
* WLAN

## 📂 Project Files

```text
📁 Public-WiFi-Mall-Network
│
├── 📄 README.md
├── 📦 Public_WiFi_Mall_Project.pkt
└── 📄 Project_Report.pdf
```

## 🎓 Academic Project

**Course:** CIS211 — Computer Networks
**Department:** Computing and Information System
**University:** Daffodil International University
**Batch:** 22
**Section:** 22A

## 👥 Team

**Team Members:**

* Md. Amzadullah Ratul
* Md. Ratul Hasan
* Samiul Islam Tamim  
* Abdullah Bin Wahed 

## 📜 License

This project was created for academic and educational purposes.

```

### github/amzadullah


**`public-wifi-mall-network`**


> Cisco Packet Tracer project designing a secure and scalable public Wi-Fi and guest network for a shopping mall.

