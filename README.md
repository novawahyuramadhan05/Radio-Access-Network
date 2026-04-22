# Radio-Access-Network
RAN simulation projects focusing on cellular coverage, signal propagation, mobility, handover, and wireless network performance.


# Radio Access Network (RAN) Simulation Projects

This repository contains a collection of simulation-based projects focused on Radio Access Network (RAN) concepts in modern wireless communication systems.

The goal is to understand how mobile devices connect to base stations, how wireless signals propagate through space, and how mobility and network performance are managed in cellular systems such as LTE and 5G.

Each concept is implemented through simplified simulations to build practical engineering intuition rather than relying only on theoretical models.

---

## Core Focus Areas

### 1. Cellular Systems & Coverage
Understanding how mobile networks are structured using cells and base stations.

Key concepts:
- Base station (BTS / eNodeB / gNodeB)
- Cell coverage area
- User Equipment (UE)
- Cellular network architecture

---

### 2. Signal Propagation & Path Loss
Understanding how wireless signals degrade over distance and environment.

Key concepts:
- Path loss models
- Signal attenuation
- Distance vs signal strength
- RSSI (Received Signal Strength Indicator)

---

### 3. Mobility & Handover
Understanding how mobile devices move between cells without losing connection.

Key concepts:
- User mobility
- Handover mechanism
- Signal threshold-based switching
- Best cell selection

---

### 4. Link Budget & Performance Analysis
Understanding whether a wireless connection is strong enough to support communication.

Key concepts:
- Transmit power
- Antenna gain
- Path loss calculation
- Received signal power
- Signal-to-Noise Ratio (SNR)

---

### 5. Multi-Cell System Simulation (Future Expansion)
Understanding large-scale behavior of cellular networks.

Key concepts:
- Multi-cell environments
- Interference between cells
- Load balancing
- Network capacity and congestion

---

## Projects in This Repository

### 1. Cellular Coverage Visualizer
Simulates base station coverage areas and visualizes user positions inside or outside a cell.

### 2. Path Loss Simulator
Models how signal strength decreases as distance increases between user and base station.

### 3. Handover Simulation Model
Simulates user movement between multiple cells and dynamic base station switching.

### 4. Link Budget Calculator
Calculates wireless link viability based on power, gain, and path loss parameters.

---

## Learning Approach

Each project follows a simplified wireless communication model:

User Device → Wireless Channel → Base Station → Network Core

The focus is on understanding physical and system-level behavior of wireless communication in cellular networks.

---

## Tech Stack

- Python
- NumPy (simulation and computation)
- Matplotlib (visualization)
- NetworkX (optional for cell/network modeling)

---

## Goal of This Repository

To build a strong conceptual understanding of how cellular networks operate from a Radio Access Network perspective, including coverage, mobility, and wireless signal behavior.

This repository is part of a larger telecommunications engineering roadmap covering:
- Network Engineering (packet and routing systems)
- Signal Processing (waveforms and modulation)
- Radio Access Network (wireless communication systems)

---

## Status

This repository is actively developed as part of a structured learning path in telecommunications engineering.
