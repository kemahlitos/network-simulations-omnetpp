# IPv4 Addressing and Routing Studies

This directory contains a set of **IPv4 network configuration and routing studies**
implemented using **OMNeT++ and the INET framework**.
The simulations focus on how IP addressing schemes and routing decisions shape
network structure and packet forwarding behavior.

Rather than performance measurement, the emphasis here is on **network configuration,
routing logic, and path control** in multi-router topologies.

---

## Focus of the Studies

The experiments in this study explore key aspects of IPv4 networking, including:

- Automatic and manual IPv4 address assignment
- Subnetting and hierarchical address organization
- Routing table construction and optimization
- Path selection and asymmetric routing behavior
- Effects of topology changes on routing decisions

Realistic address blocks and multi-router network layouts are used to reflect
practical network design considerations.

---

## Experiments Included

- **IPv4 address assignment experiments**  
  Study how hosts, routers, and subnets are assigned IP addresses and how addressing
  impacts network organization.

- **Routing behavior analysis**  
  Observe routing table formation and updates under different topologies and configurations.

- **Controlled path selection experiments**  
  Configure routing rules to enforce specific forward and return paths across the network.

- **Hierarchical routing experiments**  
  Analyze how hierarchical and optimized routing reduces routing table complexity.

Each experiment is defined through OMNeT++ configuration and topology files,
allowing reproducible network setups.

---

## Notes

The goal of this study is to demonstrate **practical understanding of IPv4 addressing
and routing mechanisms**, with a focus on configuration correctness, routing logic,
and network-level reasoning rather than raw performance metrics.

Experiments video link: https://youtu.be/k4EQS32FZmg
