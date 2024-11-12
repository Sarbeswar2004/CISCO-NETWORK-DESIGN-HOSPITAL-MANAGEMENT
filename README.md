# SOHO Network Documentation

This README provides technical specifications, setup details, and maintenance instructions for a Small Office/Home Office (SOHO) network. It serves as a reference for network setup, configuration, and ongoing management.

## Table of Contents

1. [Overview](#overview)
2. [Network Requirements](#network-requirements)
3. [Network Topology](#network-topology)
4. [Network Devices](#network-devices)
5. [IP Addressing Scheme](#ip-addressing-scheme)
6. [Device Configuration](#device-configuration)
7. [Wireless Configuration](#wireless-configuration)
8. [Security Settings](#security-settings)
9. [Backup and Redundancy](#backup-and-redundancy)
10. [Maintenance and Troubleshooting](#maintenance-and-troubleshooting)
11. [Appendices](#appendices)

## 1. Overview

- **Purpose**: Provide network connectivity for a small office, enabling internet access, local file sharing, and printer access.
- **Location**: [Specify Location]
- **Prepared By**: [Your Name]
- **Date**: [Date of Documentation]

## 2. Network Requirements

- **Devices**: Computers, printers, VoIP phones, wireless devices (laptops, smartphones).
- **Network Infrastructure**: Router, switch, wireless access point (optional if router has Wi-Fi).
- **Internet Connection**: ISP modem/router.

## 3. Network Topology

- **Diagram**: See the topology diagram in the [Appendices](#appendices).
- **Description**:
  - All devices connect to a main router for internet and LAN access.
  - Wired connections for desktops, wireless for mobile devices.
  - Printer and file server are accessible over the LAN.

## 4. Network Devices

### Router
- **Model**: [Router Model and Brand]
- **IP Address**: 192.168.1.1 (Default Gateway)
- **Subnet Mask**: 255.255.255.0
- **Settings**: DHCP enabled (range 192.168.1.10 – 192.168.1.100)
- **Firewall**: Enabled
- **Port Forwarding**: [Specify if required]

### Switch (Optional)
- **Model**: [Switch Model]
- **Ports**: [Number of Ports]

### Access Point (if separate from router)
- **Model**: [Access Point Model]
- **SSID**: [Network Name]
- **Password**: [WPA2 Password]
- **IP Address**: Static IP (e.g., 192.168.1.2)

## 5. IP Addressing Scheme

- **Network ID**: 192.168.1.0/24
- **Router IP (Gateway)**: 192.168.1.1
- **DHCP Range**: 192.168.1.10 - 192.168.1.100
- **Static IPs**:
  - Printer: 192.168.1.101
  - File Server: 192.168.1.102
  - VoIP Phones: 192.168.1.103 - 192.168.1.105

## 6. Device Configuration

- **Computers**: Obtain IP via DHCP.
- **Printers & File Servers**: Static IPs.
- **VoIP Phones**: Direct connection for voice traffic.

## 7. Wireless Configuration

- **SSID**: [Network Name]
- **Security**: WPA2 or WPA3
- **Password**: [Network Password]
- **Guest Network**: Enabled/Disabled

## 8. Security Settings

- **Firewall**: Enabled on router.
- **MAC Filtering**: Optionally enabled.
- **Guest Network Isolation**: Enabled.
- **Encryption**: WPA2/WPA3 for wireless.

## 9. Backup and Redundancy

- **Backup Router**: Optional secondary router for failover.
- **ISP Backup**: Optional cellular or secondary ISP.
- **Power Backup**: UPS for router and essential devices.

## 10. Maintenance and Troubleshooting

- **Firmware Updates**: Regular updates on router and network devices.
- **Monitoring**: Enable logging for network usage and issues.
- **Troubleshooting Guide**:
  - **No Internet**: Check ISP, router status, and cables.
  - **Slow Speed**: Restart router, check device load, adjust Wi-Fi channel.
  - **Device Not Connecting**: Check IP settings, reset DHCP.

## 11. Appendices

- **Network Topology Diagram**: ![Topology Diagram](path/to/topology-diagram.png)
- **Device List**: Table of devices, IP addresses, MAC addresses, and locations.
- **IP Address Assignment Table**: Detailed IP allocation for connected devices.

---

For any questions or troubleshooting assistance, please contact [Your Contact Information].
