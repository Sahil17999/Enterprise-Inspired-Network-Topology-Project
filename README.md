# Enterprise-Inspired-Network-Topology-Project

<img width="1132" height="498" alt="Screenshot 2026-03-08 at 6 38 39 PM" src="https://github.com/user-attachments/assets/349ac896-7350-4326-ba9f-634ba483a943" />

## Project Description

This project is a simplified network lab designed to demonstrate the core concepts behind how enterprise networks connect internal infrastructure to the internet. The design was inspired by the type of large-scale network topology used in enterprise environments. While working at DCM, I became interested in how enterprise networks are structured and how routers, WAN links, and external connectivity are organized.

This lab is not intended to replicate a real production network. Instead, it is an **oversimplified educational model** that captures the basic idea of how enterprise routers connect to each other and to the internet through WAN links.

The topology uses multiple routers connected through **serial WAN interfaces**, along with a simulated internet router. A **loopback interface** is used to represent a public internet destination. This allows the lab to demonstrate how internal routers communicate with an external network.

## Goals of the Project

The goal of this project is to practice and demonstrate:

* Basic router configuration
* WAN interface configuration
* IP addressing for point-to-point links
* Simulating internet connectivity using loopback interfaces
* Troubleshooting interface and connectivity issues

## Requirements

To view and run the network topology used in this project, you must install **Cisco Packet Tracer**.

### Steps

1. Download and install **Cisco Packet Tracer** from the Cisco Networking Academy website.
2. Open the `.pkt` file included in this repository.
3. Explore the topology and review the router configurations.
4. Use the CLI within Packet Tracer to practice and test the commands used in the lab.

Packet Tracer allows you to simulate real networking equipment and interact with routers and interfaces as you would in a real environment.

## Documentation

This repository also includes a **complete guide PDF** that explains the lab in detail.

The document covers:

* Step-by-step configuration of the topology
* Explanation of the networking concepts used
* How each protocol in the lab works
* Command breakdowns and troubleshooting steps

You can find the guide in the repository as:

```
enterprise-network-guide.pdf
```

This document was created to make it easier for learners to understand the configuration process and the reasoning behind each step.

