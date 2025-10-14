# Cisco Networking Labs

This repository contains a collection of networking labs completed as part of the **Computer Systems** module.  
All labs are built using **Cisco Packet Tracer** and focus on practical networking concepts such as topology design, VLANs, routing, DHCP, and network security.

## Labs

### 1. Network Topologies
- Explore **bus, star, ring, mesh, and hybrid** topologies  
- Learn about scalability, fault tolerance, and performance trade-offs  
- Practice device setup, cabling, IP addressing, and connectivity testing  

### 2. Router and Subnet Configuration
- Designed a **four-subnet topology** connected via a central router  
- Configured **default gateways** and **subnets** for each network segment  
- Verified end-to-end connectivity between PCs across subnets using **ping** and **traceroute**  
- Implemented logical segmentation using **Switch-PT** and **Router-PT** devices  
- Demonstrated basic **inter-network communication** setup and subnet isolation  

### 3. Static Routing Between Four Networks
- Implemented **static routing** to connect four separate LANs through a single central router  
- Manually configured **route statements** to define network paths for each subnet  
- Assigned IP addresses to interfaces and set up **default gateways** for each network  
- Verified full **inter-network connectivity** between all PCs using **ICMP (ping)** tests  
- Demonstrated the use of `ip route` commands for manual route management  
- **Topology:** One central router connecting four LANs (green, yellow, blue, red)  

### 4. RIP Routing Between Multiple Networks
- Configured **Routing Information Protocol (RIP)** to enable dynamic routing between three interconnected routers  
- Added multiple **network statements** to advertise local subnets  
- Verified **route propagation** and **connectivity** between PCs in separate LANs  
- Demonstrated dynamic route updates without manual static route configuration  
- Used `Router(config-router)#network <address>` commands for RIP configuration  
- **Topology:** Three routers (Router2, Router3, Router4) interconnecting three LANs with switches and end devices  

