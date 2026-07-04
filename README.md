# Pi-hole DNS Server

## Project Overview

This project documents the deployment of a Pi-hole DNS server used to provide network-wide ad and tracker blocking for my home network.

The project also gave me practical experience with Linux administration, DHCP configuration and home network management.

---

# Objectives

- Block advertisements across the entire home network
- Learn DNS and DHCP fundamentals
- Improve Linux administration skills
- Gain experience configuring network infrastructure

---

# Hardware

- Raspberry Pi 3B+
- MicroSD Card
- Home Network
- Virgin Media Hub 5
---

# Software

- Raspberry Pi OS
- Pi-hole
- Web Administration Interface

---

# Network Configuration

The Virgin Media router DHCP service was disabled.

Pi-hole was configured to provide DHCP services so every device connecting to the home network automatically used Pi-hole for DNS resolution.

---

# Challenges

The biggest challenge was configuring the Virgin Media router correctly.

Disabling the router DHCP service and allowing Pi-hole to become the DHCP server required troubleshooting before all devices were able to obtain the correct network configuration.

---

# Skills Demonstrated

- Linux Administration
- DNS
- DHCP
- Home Networking
- Raspberry Pi
- Troubleshooting

---

# Lessons Learned

This project helped me understand how DNS requests are processed inside a home network and how DHCP controls which DNS server clients receive.

It also improved my troubleshooting skills when working with network devices.
