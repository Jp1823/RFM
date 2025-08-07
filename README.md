# RFM Project – Mobile and Physical Networks

This repository documents the work developed for the **RFM** course, part of the **RNG profile** in the 2nd semester at the **University of Minho**.

The project is divided into **three phases**, each exploring a distinct area within the scope of **mobile and physical networks**.

---

## 📍 TP 1 – Access Technologies and Packet Analysis with CORE

In the first phase, we were tasked with selecting and evaluating one access technology, from among several, to be integrated into a test topology.

Using the **CORE network emulator**, we built different scenarios to observe network behavior. Tools such as `iperf`, `ping`, and `traceroute` were employed to analyze traffic performance under different configurations.

---

## 📍 TP 2 – MPLS Topology and Traffic Engineering with EVE-NG

The second phase focused on building an **MPLS-based topology** using the **EVE-NG platform**.

- The network connected multiple **customer devices (CEs)** to **provider edge routers (PEs / LERs)**.
- Inside the core, **provider routers (P routers / LSRs)** were responsible for **label switching** across established tunnels.
- **Traffic engineering** techniques were applied using **Access Control Lists (ACLs)** and **Policy-Based Routing (PBR)** to create specific tunnels for different types of traffic (e.g., HTTP and UDP).
- This approach enabled **differentiated routing paths** within the network, enhancing control over how traffic is handled.

---

## 📍 TP 3 – 5G Network Core Simulation with Free5GC and UERANSIM

The final phase aimed to provide practical insight into the operation of a **5G mobile network**.

- We used the **Free5GC** open-source 5G core implementation to simulate the core network.
- To emulate **mobile devices (UEs)** and the **5G base station (gNodeB)**, we used **UERANSIM**.
- Through this setup, we simulated mobile connections and analyzed the roles of various **Network Functions (NFs)** in tasks such as:
  - **Mobility management**
  - **Authentication**
  - **Session establishment**
  - **Traffic routing** to the Internet
