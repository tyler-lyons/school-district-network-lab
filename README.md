# School District Network Lab

A multi-phase Cisco Packet Tracer project that models a simulated scalable school district network.

## Skills Demonstrated

- VLAN segmentation
- DHCP configuration and relay
- Router-on-a-stick inter-VLAN routing
- Wireless network configuration
- Switch trunking
- Access Control Lists (ACLs)
- Network troubleshooting and validation

## Project Phases

### Phase 1: Small Office Network
Created wired Administration and Staff Wi-Fi networks with DHCP and inter-VLAN routing.

### Phase 2: Department Segmentation
Added Student, Guest Wi-Fi, and Printers/IoT VLANs.

### Phase 3: Access Control
Applied ACLs to restrict Student and Guest access to protected internal networks.

## Network Segmentation

| VLAN | Department | Network |
|---:|---|---|
| 10 | District Administration | 192.168.10.0/24 |
| 20 | Faculty & Staff Wi-Fi | 192.168.20.0/24 |
| 30 | Students | 192.168.30.0/24 |
| 40 | Guest Wi-Fi | 192.168.40.0/24 |
| 50 | Printers/IoT | 192.168.50.0/24 |

## Validation

- Verified DHCP leases for each VLAN.
- Confirmed inter-VLAN routing before ACL implementation.
- Confirmed Student and Guest ACL restrictions after Phase 3.
