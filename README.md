# VPN/MPLS Network Implementation Project

## Project Overview
This project is part of a **networking course lab**, focusing on designing and implementing a VPN/MPLS network for the company CSIQ. The goal is to ensure secure and confidential connectivity between 6 remote sites (1 central site, 3 stores, and 2 factories) using MPLS technology provided by an operator.  

## Key Tasks
1. **Addressing Plan**: Design an IP addressing scheme for the sites and the provider's network, using `/24` prefixes for CE-connected networks and `/30` for point-to-point links.
2. **Dynamic Routing Configuration**:
   - Configure RIP between CE1-PE1, CE2-PE2, and CE3-PE3.
   - Configure EIGRP between CE4-PE3, CE5-PE4, and CE6-PE4.
   - Use OSPF within the provider's backbone (PE and P routers).
3. **MPLS Implementation**: Enable MPLS switching within the provider's network.
4. **VPN Architecture**:
   - **Hub & Spoke VPN**: Connect the 3 stores to the HQ, requiring traffic between stores to pass through the HQ.
   - **Full Mesh VPN**: Direct connectivity between the 2 factories and the HQ.
