
# IP Addressing Plan

## Management Network

Network: 10.10.10.0/24

| Device | Interface | IP Address |
|--------|-----------|------------|
| R1 | eth0 | 10.10.10.1 |
| SW1 | VLAN1 | 10.10.10.100 |
| SRV-AAA | eth0 | 10.10.10.10 |
| PC-ADMIN | eth0 | 10.10.10.20 |

## Configuration

All devices use static IPv4 addressing.

Subnet mask: 255.255.255.0

Default gateway: 10.10.10.1
