# Day 01 - Network Devices & Enterprise Topology

## Overview

This lab was completed as part of my networking studies using Cisco Packet Tracer.

The purpose of this exercise was to become familiar with common network devices found in enterprise environments and understand how those devices work together to provide connectivity and security across multiple locations.

The topology simulates a company with two branch sites connected through a central internet router, plus an external attacker system to illustrate the role of perimeter security.

## Devices Used

- 2x Routers (Router1, Router2) — branch edge routers
- 1x Router (Internet) — central router connecting both branches
- 2x Firewalls (Fw1, Fw2) — one per branch
- 2x Switches (Switch1, Switch2)
- 2x PCs (PC1, PC2)
- 1x Laptop (user)
- 2x Servers (Server1, Server2)
- 1x Laptop (Attacker) — represents an external threat actor

## Network Design

Each branch follows the same pattern: end devices connect to a switch, the switch connects to a router, and the router connects through a firewall before reaching the internet. Both branches meet at a central router representing the internet.

**Traffic Flow:** PC/Server → Switch → Router → Firewall → Internet

## What I Learned

- How routers, switches, firewalls, and endpoints connect to form a basic enterprise network
- The role of a firewall at the edge of a branch network
- Why organizations place firewalls and use layered security to protect internal resources from external threats
- How multiple branch sites can connect through a shared internet router

## Status

Topology built — interfaces not yet configured (IP addressing is the next step).
