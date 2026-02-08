# Wired Network Performance Analysis

This directory contains a set of **wired Ethernet network experiments** implemented using **OMNeT++ and the INET framework**.
The experiments focus on understanding how traffic characteristics and link parameters affect
core network performance metrics.

Each experiment is configured via separate OMNeT++ `.ini` files, allowing controlled variation
of parameters and repeatable measurements.

---

## Focus of the Experiments

The simulations in this study analyze the behavior of wired packet-switched networks under
different operating conditions, with emphasis on:

- Channel throughput and saturation effects
- Link utilization under varying traffic load
- Transmission, propagation, and queuing delays

Traffic generation follows stochastic arrival patterns, and experiments are executed with
different parameter configurations to observe performance trends.

---

## Experiments Included

- **Throughput experiments**  
  Analyze how packet interarrival time and link bitrate affect achievable throughput and saturation behavior.

- **Utilization experiments**  
  Examine channel utilization as traffic load increases and identify operating regions where the link becomes saturated.

- **Propagation time experiments**  
  Measure the impact of link properties on packet propagation delay.

Each experiment is defined and reproducible through its corresponding OMNeT++ configuration file.

---

## Notes

The purpose of this study is to demonstrate **performance-oriented network analysis**
through simulation, highlighting the relationship between offered load, link capacity,
and observable network behavior.

