# Network Simulations with OMNeT++

This repository contains a collection of **computer network simulation studies** implemented using **OMNeT++ and the INET framework**.  
The simulations focus on modeling, configuring, and analyzing network behavior under different technologies, protocols, and traffic conditions.

Rather than isolated examples, each study is designed as an **experiment-driven network analysis**, exploring how design choices and parameters affect performance, routing behavior, and protocol dynamics.

---

## Scope and Objectives

The primary goal of this repository is to demonstrate practical **network-level reasoning** through discrete-event simulation.  
The studies cover both **wired and wireless networks**, as well as **IPv4 addressing and routing configurations**, with an emphasis on measurable performance metrics and protocol behavior.

Across the simulations, the following questions are explored:

- How does traffic load affect throughput, delay, and queuing behavior?
- How do link parameters such as bitrate, error rate, and packet size influence performance?
- How does network topology and routing configuration impact end-to-end behavior?
- How do wireless channel characteristics and MAC protocols affect communication quality?

---

## Simulation Environment

- Simulator: **OMNeT++**
- Framework: **INET**
- Modeling approach: Discrete-event network simulation
- Experiments executed using multiple parameter configurations and repeated runs where applicable

Typical metrics analyzed include:
- Throughput and channel utilization
- End-to-end delay and packet delay variation (jitter)
- Transmission, propagation, and queuing delays
- Routing behavior and path selection
- Wireless channel capacity and protocol performance

---

## Studies Overview

### Wired Network Performance Analysis

This study focuses on **wired Ethernet-based networks**, analyzing how traffic characteristics and link parameters influence network performance.

Key aspects explored include:
- Throughput and channel utilization under varying traffic loads
- Effects of interarrival time, bitrate, and packet length
- End-to-end delay, jitter, and queuing behavior
- Impact of bit error rate (BER) and multi-hop switch topologies

The simulations emphasize performance saturation, congestion effects, and delay dynamics in packet-switched wired networks.

---

### IPv4 Addressing and Routing Studies

This study examines **IPv4 network configuration and routing behavior** in multi-router topologies.

The simulations focus on:
- Automatic and manual IP address assignment
- Use of real-world IP address blocks
- Routing table construction and updates
- Hierarchical and optimized routing configurations
- Controlled path selection and asymmetric routing scenarios

The goal is to understand how addressing schemes and routing decisions affect network structure and packet forwarding behavior.

---

### Wireless Network Behavior Analysis

This study explores **wireless network behavior** using INET’s wireless models.

Key topics include:
- Effects of node placement and distance on communication quality
- Wireless channel capacity over time
- Impact of physical topology changes on performance metrics
- Comparison of different MAC protocols under identical conditions

The simulations highlight the interaction between physical layer assumptions, medium access protocols, and observable network performance.

---

## Organization

Each directory in this repository represents a **self-contained simulation study**.
Within each study:
- Network topologies are defined using `.ned` files
- Simulation parameters and experiment variants are configured via `.ini` files
- Additional documentation explains the intent, setup, and observations for the simulations

This structure allows each study to be understood and executed independently.

---

## Notes

These simulation studies were developed in an advanced computer networking context and are presented here as standalone examples of **network modeling, configuration, and performance analysis** using OMNeT++.

The emphasis of the repository is on **conceptual understanding, experimental design, and interpretation of results**, rather than on a single fixed network scenario.
