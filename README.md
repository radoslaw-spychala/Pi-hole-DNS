# Pi-hole DNS Server

![Status](https://img.shields.io/badge/status-active-success)
![Platform](https://img.shields.io/badge/platform-Raspberry%20Pi-red)
![OS](https://img.shields.io/badge/OS-Raspberry%20Pi%20OS-green)
![License](https://img.shields.io/badge/license-MIT-blue)

## Project Overview

This project documents the deployment of a Pi-hole DNS server running on a Raspberry Pi 3B+ with a dedicated 5-inch display housed in a custom 3D-printed enclosure.

The system provides network-wide DNS filtering and DHCP services for my home network, improving privacy, reducing advertisements and giving me practical experience with Linux administration, networking and self-hosted infrastructure.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Hardware](#hardware)
- [Software](#software)
- [Project Specifications](#project-specifications)
- [Network Configuration](#network-configuration)
- [Installation](#installation)
- [Challenges](#challenges)
- [Results](#results)
- [Skills Demonstrated](#skills-demonstrated)
- [Lessons Learned](#lessons-learned)
- [Future Improvements](#future-improvements)

## Objectives

- Block advertisements across the entire home network
- Learn DNS and DHCP fundamentals
- Improve Linux administration skills
- Gain experience configuring network infrastructure

---

## Hardware

- Raspberry Pi 3B+
- 32 GB MicroSD Card
- OSOYOO 5-inch HDMI Display
- Custom 3D-printed enclosure
- Virgin Media Hub 5
  
---

## Software

- Raspberry Pi OS
- Pi-hole
- Pi-hole Web Interface
- Cloudflare DNS (Upstream Resolver)

---

## Project Specifications

| Item | Value |
|------|-------|
| Platform | Raspberry Pi 3B+ |
| Operating System | Raspberry Pi OS |
| DNS Server | Pi-hole |
| DHCP Server | Pi-hole |
| Upstream DNS | Cloudflare |
| Router | Virgin Media Hub 5 |
| Network Type | Home LAN |

## Network Configuration

The Virgin Media router DHCP service was disabled.

Pi-hole was configured to provide DHCP services so every device connecting to the home network automatically used Pi-hole for DNS resolution.

---

## Installation

The installation process included:

1. Installing Raspberry Pi OS.
2. Installing Pi-hole using the official installation script.
3. Configuring Cloudflare as the upstream DNS provider.
4. Disabling DHCP on the Virgin Media Hub 5.
5. Enabling the Pi-hole DHCP server.
6. Testing DNS resolution from multiple client devices.

## Challenges

The biggest challenge was configuring the Virgin Media router correctly.

Disabling the router DHCP service and allowing Pi-hole to become the DHCP server required troubleshooting before all devices were able to obtain the correct network configuration.

---

## Skills Demonstrated

- Linux Administration
- DNS
- DHCP
- Home Networking
- Raspberry Pi
- Troubleshooting

---

## Features

- Network-wide advertisement blocking
- DNS filtering
- DHCP server
- Cloudflare upstream DNS
- Web administration interface
- Real-time query logging
- Raspberry Pi deployment
- Custom 3D-printed enclosure
- Dedicated 5-inch display

## Results

The completed deployment provides:

- Network-wide DNS filtering
- Network-wide advertisement blocking
- DHCP management
- Centralised DNS administration
- Web-based monitoring interface
- Reliable operation for all connected home devices

## Lessons Learned

This project helped me understand how DNS requests are processed inside a home network and how DHCP controls which DNS server clients receive.

It also improved my troubleshooting skills when working with network devices.

## Future Improvements

Planned future improvements include:

- Enable encrypted DNS (DoH or DoT)
- Improve dashboard monitoring
- Add network monitoring
- Improve physical cable management
- Integrate additional self-hosted services
