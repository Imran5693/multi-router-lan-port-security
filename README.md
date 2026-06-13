# Multi-Router LAN with Wireless Integration and Port Security Simulation

## Overview

This project demonstrates the design and implementation of a secure multi-segment enterprise network using Cisco Packet Tracer. The simulation integrates routed LAN environments, wireless connectivity, dynamic routing, and access control mechanisms to protect the network against unauthorized devices.

The objective was to create a realistic enterprise-style topology where legitimate users maintain seamless connectivity while rogue or unauthorized devices are automatically restricted through multiple security controls.

---

## Network Architecture

The topology consists of two routed network segments connected through Cisco routers running RIP version 2.

### Network-A

* Subnet: 192.168.1.0/24
* Switch-A
* PC-A
* Wireless Access Point A
* Laptop-A

### Network-B

* Subnet: 192.168.2.0/24
* Switch-B
* PC-B
* Wireless Access Point B
* Laptop-B

### Inter-Router Link

* Network: 192.168.0.0/24
* RIP v2 enabled

This architecture demonstrates how geographically separated LANs can communicate through dynamic routing while maintaining secure local access.

---

## Key Features

### Dynamic Routing (RIP v2)

* Automatic route advertisement
* Multi-network communication
* Routing table propagation
* End-to-end connectivity validation

### Wireless Integration

* Wireless access points deployed on both LAN segments
* WPA2-secured wireless access
* Authorized client connectivity
* Mobility support within the network

### Port Security

Switch access ports are configured with security policies that:

* Restrict unauthorized MAC addresses
* Limit device connections
* Detect rogue device insertion attempts
* Generate security violations

### Rogue Device Mitigation

The project demonstrates how unauthorized endpoints are blocked using:

* Port Security
* MAC Address Control
* Wireless Access Restrictions

### Network Segmentation

The topology separates users into different LAN segments while maintaining controlled communication between networks through routing.

---

## Security Controls Implemented

| Security Control         | Purpose                                |
| ------------------------ | -------------------------------------- |
| Port Security            | Prevent unauthorized wired devices     |
| MAC Address Restrictions | Limit endpoint access                  |
| WPA2 Wireless Security   | Secure wireless communications         |
| LAN Segmentation         | Isolate network domains                |
| RIP v2 Routing           | Controlled inter-network communication |

---

## Validation & Testing

The following tests were performed:

* Successful ping tests between LAN segments
* Router connectivity verification
* RIP route propagation validation
* Wireless client connectivity testing
* Rogue device blocking demonstration
* Port security violation testing

Results confirmed secure communication for authorized users while preventing unauthorized network access.

---

## Technologies Used

### Network Simulation

* Cisco Packet Tracer

### Devices

* Cisco 2811 Routers
* Cisco 2960 Switches
* Wireless Access Points
* PCs
* Laptops

### Protocols & Services

* IPv4 Addressing
* RIP Version 2
* Wireless Networking
* WPA2 Security
* Port Security
* MAC Filtering

---

## Learning Outcomes

This project provided practical experience with:

* Enterprise LAN Design
* Multi-Router Connectivity
* Dynamic Routing
* Wireless Network Deployment
* Network Access Control
* Port Security Configuration
* Rogue Device Detection
* Layer 2 & Layer 3 Security Concepts

---

## Repository Contents

```text
multi-router.pkt
screenshots/
report/
video_links.md
README.md
```

### Files

* multi-router.pkt → Cisco Packet Tracer simulation
* screenshots/ → Topology and verification screenshots
* report/project_report.pdf → Detailed technical report
* video_links.md → Demonstration video links

---

## Demonstration

YouTube Walkthrough:

https://youtu.be/0MyrHqR190Y

---

## Author

Imran Sarwar

Network Operations | Infrastructure | Network Security | Automation
