# RPL-Cooja-LLN-Analysis
Analysis of RPL Routing Protocol for Low Power and Lossy Networks using the Cooja Simulator
# Using the Cooja Simulator: Analysing the Routing Protocol (RPL) for Low Power and Lossy Networks in IoT

## Authors

* Dr. Anil Behal
* Dr. Jasminder Kaur Sandhu
* Dr. Ganesh Gupta

---

## Abstract

The Internet of Things (IoT) has emerged as one of the most flexible and rapidly growing technological domains. Routing Protocol for Low Power and Lossy Networks (RPL) is a specialized IPv6-based routing protocol designed for resource-constrained IoT environments.

This project presents an implementation and analysis of RPL using the Cooja Simulator within the Contiki Operating System. The study demonstrates how RPL constructs a Destination-Oriented Directed Acyclic Graph (DODAG) and enables efficient communication among low-power devices. The simulation illustrates route formation, packet forwarding, and network establishment in Low Power and Lossy Networks (LLNs).

---

## Keywords

* Internet of Things (IoT)
* RPL
* LLN
* DODAG
* Cooja Simulator
* Contiki OS
* IPv6
* 6LoWPAN
* Wireless Sensor Networks

---

## Research Objectives

* Analyze the operation of RPL in IoT environments.
* Study DODAG formation and route establishment.
* Understand the exchange of DIO, DIS, and DAO messages.
* Evaluate routing behaviour in Low Power and Lossy Networks.
* Demonstrate practical implementation using the Cooja Simulator.

---

## Technologies Used

| Technology      | Purpose                |
| --------------- | ---------------------- |
| Contiki OS      | IoT Operating System   |
| Cooja Simulator | Network Simulation     |
| RPL             | Routing Protocol       |
| IPv6            | Network Layer Protocol |
| 6LoWPAN         | IPv6 Adaptation Layer  |
| IEEE 802.15.4   | Wireless Communication |

---

## Network Architecture

RPL creates a routing topology known as a Destination-Oriented Directed Acyclic Graph (DODAG).

Key control messages:

* DIO (DODAG Information Object)
* DIS (DODAG Information Solicitation)
* DAO (Destination Advertisement Object)

These messages help nodes discover neighbours, construct routing paths, and maintain network stability.

---

## Simulation Setup

The simulation environment consists of:

* 1 Receiver Node
* Multiple Sender Nodes
* Sky Motes
* RPL Unicast Communication
* Contiki OS Environment

The network is executed using the Cooja Simulator where nodes establish routes dynamically through DODAG construction.

---

## Results

The simulation demonstrates:

* Successful DODAG formation.
* Route establishment between sender and receiver nodes.
* Exchange of RPL control messages.
* Efficient packet forwarding.
* Stable communication in Low Power and Lossy Networks.

### Observations

* RPL successfully selects preferred parent nodes.
* Nodes maintain backup routes for fault tolerance.
* Trickle Algorithm efficiently controls DIO transmission.
* Network topology adapts dynamically to communication requirements.

---

## Research Contributions

This work provides:

* Practical implementation of RPL using Cooja.
* Visualization of DODAG creation.
* Analysis of packet routing mechanisms.
* Understanding of LLN routing behaviour in IoT systems.

---

## Future Work

Potential extensions include:

* Reinforcement Learning based routing.
* Energy-aware RPL optimization.
* Drone-assisted IoT communication.
* Load balancing in LLNs.
* AI-enabled routing decisions.
* Cross-layer optimization techniques.

---

## Repository Structure

RPL-Cooja-LLN-Analysis/

├── README.md

├── Paper/

├── Simulations/

├── Results/

├── Images/

└── Documentation/

---

## Citation

If you use this work in your research, please cite:

Anil Behal, Jasminder Kaur Sandhu, and Ganesh Gupta.

"Using the Cooja Simulator: Analysing the Routing Protocol (RPL) for Low Power and Lossy Networks in IoT."

---

## Contact

Dr. Anil Behal

Assistant Professor (Computer Science & Engineering)

Research Interests:

* Internet of Things (IoT)
* Low Power and Lossy Networks
* Computer Networks
* Routing Protocols
* Drone Networking
* Artificial Intelligence in Networking

Research collaborations and academic contributions are welcome.
