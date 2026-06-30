# Home Network Lab — Wired + Wireless Connectivity with DHCP

## Overview
A small home network built in Cisco Packet Tracer with one wired PC and one wireless laptop, both connected through a home router. The goal was to understand how DHCP, wireless association, and basic device discovery work together in a real network.

## What I Did
- Set up a home router with one wired PC and one wireless laptop
- Installed and configured a WPC300N wireless adapter on the laptop
- Connected the laptop to the router's wireless network
- Configured DHCP so both devices received IP addresses automatically
- Verified end-to-end connectivity with a successful ping between the wired and wireless devices
- Used Simulation mode to inspect a gratuitous ARP broadcast at Layer 2, observing how a device announces its newly assigned IP to the network

## Key Takeaway
Watching DHCP assignment and the resulting gratuitous ARP broadcast in real time made it clear how much background negotiation happens the moment a device joins a network — fundamentals that matter for both troubleshooting and later traffic analysis.

## Tools Used
Cisco Packet Tracer (Realtime + Simulation Mode)

## Screenshots

![Network Topology](topology.jpeg)

![Successful Ping](ping_success.jpeg)

![Gratuitous ARP Packet Capture](arp_packet.jpeg)

## Files
- `.pkt` project file included in this repository (open with Cisco Packet Tracer)
