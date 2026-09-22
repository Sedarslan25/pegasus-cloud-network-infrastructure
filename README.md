# Cloud & Network Infrastructure Simulation

A Cisco Packet Tracer and VirtualBox infrastructure-design project that models a secure, scalable airline enterprise network. The scenario connects headquarters and an airport branch through an OSPF-routed WAN and centralizes Web, Mail, and DNS services.

> **Kısa Türkçe özet:** Genel merkez ile havalimanı şubesi arasındaki OSPF yönlendirmeli WAN’ı, sanallaştırma ortamını ve merkezi Web/Mail/DNS servislerini modelleyen bulut ve ağ altyapısı simülasyonu.

## Architecture

- Two LAN segments: `192.168.1.0/24` and `192.168.2.0/24`
- `10.0.0.0/24` WAN backbone
- OSPF dynamic routing in Area 0
- Cisco 2911 routers and Packet Tracer topology
- Virtualized Windows Server and client scenario
- Central Web, Mail, and DNS services with a PaaS-oriented design

## Contents

- `Pegasus_Network_Projesi.pkt` — runnable Cisco Packet Tracer topology
- `docs/` — technical design, system-analysis, configuration, and authentic system screenshots

## Run

1. Install Cisco Packet Tracer.
2. Open `Pegasus_Network_Projesi.pkt`.
3. Inspect routing tables and verify inter-site connectivity with ping tests.

## Notes

This is an academic infrastructure simulation for a company scenario. It does not use, expose, or claim to represent a production environment of the named company.

## Tools

Cisco Packet Tracer, Oracle VM VirtualBox, OSPF, WAN routing, network services
