# Basic-VLAN-Network
What is VLAN?
A Virtual Local Area Network (VLAN) allows network administrators to logically divide a single physical switch into multiple broadcast domains. This improves security, reduces unnecessary traffic, and provides better network management.

# Lab Overview
In this Packet Tracer lab:
- A single switch is used to configure **two VLANs**.  
- PCs are grouped based on VLAN assignment:  
  - VLAN 10 (192.168.10.0/24): PC0, PC1  
  - VLAN 20 (192.168.20.0/24): PC2, PC3  

# Key Concepts
1. **Segmentation:** Each VLAN acts as a separate LAN, even if devices are connected to the same switch.  
2. **Broadcast Control:** VLANs limit broadcast traffic within their own group.  
3. **Security:** Devices from different VLANs cannot directly communicate without a Layer 3 device (Router-on-a-Stick or L3 Switch).  
4. **Scalability:** VLANs make it easy to group users logically (e.g., by department).  

# Outcomes & Learnings
- Devices in **the same VLAN** (PC0 ↔ PC1 or PC2 ↔ PC3) can successfully ping each other.  
- Devices in **different VLANs** (e.g., PC0 ↔ PC2) cannot communicate without routing.  
- VLANs provide a foundation for secure, efficient, and manageable enterprise networks.  

# Benefits
- Enhanced security by isolating traffic.  
- Reduced broadcast traffic.  
- Simplified network management. 
- Supports future inter-VLAN routing setups. 
