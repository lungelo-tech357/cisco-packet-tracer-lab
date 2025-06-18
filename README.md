# Small Office Network (Cisco Packet Tracer)

## 📘 Overview
This project simulates a small business network infrastructure using Cisco Packet Tracer. It showcases key networking concepts like VLAN segmentation, inter-VLAN routing, DHCP, DNS, NAT, and access control.

## 🧰 Topology Components
- 1 Router (Edge)
- 2 Layer 2 Switches
- 1 Layer 3 Switch
- 6–9 PCs (3 Departments: Admin, Finance, IT)
- 1 Server (DHCP/DNS/Web)
- 1 Cloud (for simulated WAN)

## 📡 Network Design
| Department | VLAN ID | Subnet | Gateway |
|------------|---------|--------|---------|
| Admin      | 10      | 192.168.10.0/24 | .1 |
| Finance    | 20      | 192.168.20.0/24 | .1 |
| IT         | 30      | 192.168.30.0/24 | .1 |
| Server     | 99      | 192.168.99.0/24 | .1 |

## 🔐 Features Configured
- VLANs and inter-VLAN routing
- DHCP server and IP pools
- DNS resolution
- NAT to simulate internet access
- Access Control Lists for VLAN isolation
- Basic device security (passwords and banners)

## 🧪 How to Use
1. Open the `.pkt` file in Cisco Packet Tracer 8.2 or higher
2. Power on devices
3. Use `ping` and `nslookup` to test connectivity and DNS
4. View device configs for CLI commands

## 📁 Files Included
- `small-office-network.pkt`
- `topology-diagram.png`
- `device-configs.txt`
- `README.md` (this file)
