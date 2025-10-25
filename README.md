# Experiment 8 – VLAN Design and Simulation

## 🎯 Aim
To design and simulate VLANs on a switch/router using Cisco Packet Tracer.

## 🛠 Requirements
- Cisco Packet Tracer (or GNS3)
- One switch
- One router
- Four PCs

## 📖 Theory
A Virtual LAN (VLAN) is a logical LAN that allows devices to be grouped together even if they are not physically connected to the same switch.  
Each VLAN acts as a separate subnet or broadcast domain. Communication between VLANs requires a router or a Layer 3 switch.  

By configuring VLANs, we can:
- Improve network efficiency by reducing broadcast traffic.
- Enhance security by isolating groups of devices.
- Simplify network management.

In this experiment, we configure **two VLANs**:
- VLAN 10 → *SALES*  
- VLAN 20 → *IT*  

## ⚙️ Procedure
1. **Create the network topology** in Cisco Packet Tracer with 1 switch, 1 router, and 4 PCs.  
2. **Configure VLANs on the switch**:
   ```bash
   Switch> enable
   Switch# configure terminal
   Switch(config)# vlan 10
   Switch(config-vlan)# name SALES
   Switch(config)# vlan 20
   Switch(config-vlan)# name IT
