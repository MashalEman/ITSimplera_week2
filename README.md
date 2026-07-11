# Week 2 – IP Addressing (FLSM & VLSM) and VLAN Configuration

**Program:** Network Administration Internship – IT-SIMPLERA Institute
**Supervisor:** Jawad Qayum (Senior Network Administrator)

## Overview
FLSM/VLSM subnetting exercises combined with a hands-on VLAN lab, implemented in both Cisco Packet Tracer and GNS3.

## What Was Done
- Solved 10 FLSM problems and 5 VLSM design scenarios (network/broadcast address, subnet mask, usable range).
- **Packet Tracer:** Router-on-a-stick topology — Router1, Switch0, Switch1, 6 PCs — with VLAN 10 (Sales), VLAN 20 (HR), VLAN 30 (IT), verified via `show vlan brief` and `show interfaces trunk`.
- **GNS3:** Simplified 2-switch topology (Switch1, Switch2) with 4 VPCS hosts, testing pure Layer 2 VLAN trunking for VLAN 10 (192.168.10.0/24) and VLAN 20 (192.168.20.0/24).

## Repository Structure
```
Week2-IPAddressing-VLAN/
├── README.md
├── Report.pdf / Report.docx      # Full report: worksheets, topology, config, verification
├── week2.pkt                     # Packet Tracer project
├── task2.gns3                    # GNS3 project
└── Screenshots/
    ├── pkt_ss.jpg                # Packet Tracer topology
    ├── pkt_config_ss.jpg         # show vlan brief / show interfaces trunk
    └── gns_vlan.jpg              # GNS3 topology
```

## Key Learnings
- Difference between FLSM (equal subnets) and VLSM (sized-to-need subnets, less waste).
- VLAN segmentation, access vs. trunk ports, and inter-VLAN routing via router sub-interfaces.
- Verifying and troubleshooting VLAN/trunk configs with Cisco IOS commands.
