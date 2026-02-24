# Wireless Security – Team Reports (WiFi & GNSS)

## Overview

This repository collects two academic team reports focused on wireless technologies, combining experimental measurements with security/performance analysis. The work is organized as two independent mini-projects:

- **GNSS Smartphone Spoofing**: analysis of GNSS measurements collected from an Android smartphone and evaluation of spoofing effects via software simulation.
- **WiFi Performance Lab**: performance evaluation of WiFi under different link configurations, comparing TCP and UDP behavior using practical measurements and theoretical goodput estimation.

---

## Project 1: GNSS Smartphone Spoofing

### Goal

- Analyze GNSS measurements acquired via the **GNSS Logger** Android application.
- Compare GNSS behavior in different environments (**indoor vs outdoor**).
- Evaluate the effects of potential spoofing actions through **software simulation** and discuss observable indicators.

### Experimental Methodology

- Collection of raw GNSS measurements from a smartphone.
- Environmental comparison to highlight signal instability/discontinuities and their impact on positioning.
- Spoofing simulation performed with a **meaconer** approach, introducing controlled manipulation/delays to observe how the computed position can be affected.
- Identification of anomalies useful for detection (e.g., variations in **pseudorange** and **clock bias**).

---

## Project 2: WiFi Performance Lab

### Goal

- Evaluate WiFi performance across multiple scenarios using two hosts connected to an access point.
- Compare **TCP vs UDP** behavior and quantify performance under practical conditions.
- Estimate **expected goodput** from the test configuration and compare it against measured results.

### Scenario

- **WiFi–WiFi**
- **WiFi–Ethernet**
- **Ethernet–Ethernet**

### Tools

- **iperf3** for throughput/goodput measurements
- **Wireshark** for traffic inspection and protocol-level observations

