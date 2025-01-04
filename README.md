# TELCO-PROJECT

## Overview
This project aims to design and implement a robust enterprise network that integrates multiple technologies to support secure, scalable, and efficient business operations. The design incorporates advanced networking concepts such as VLANs, EtherChannels, DMZs, voice gateways, wireless LAN controllers, and AWS cloud connectivity/ hybrid.

## Objectives
- Develop a comprehensive network topology for an enterprise environment.
- Ensure secure communication between internal and external zones using a DMZ.
- Provide seamless integration with cloud services on AWS.
- Enable high availability through EtherChannel and redundant paths.
- Support wireless and wired users with Cisco WLCs and access points.
- Implement role-specific segmentation for departments like HR, Marketing, IT Support, and Cloud Engineers.

## Tools and Technologies
- Cisco Packet Tracer
- PFSENSE Firewall
- Amazon Web Services (AWS)
- Cisco Networking Equipment (Switches, Routers, WLC)
  
## Key Components
1. **Core Network Design:**
   - A central switch (OLE-SW) as the backbone.
   - EtherChannel used for link aggregation to improve bandwidth and reliability.

2. **Departmental Segmentation:**
   - VLANs configured for HR, Marketing, Admin, IT Support, Software Engineers, and Cloud Engineers.
   - Wireless and wired devices supported in each department.

3. **Security Features:**
   - Perimeter firewall (PFSENSE-FW) deployed to separate internal and external zones.
   - DMZ zone with ERP, email, and file storage servers for controlled external access.

4. **Cloud Integration:**
   - AWS S3 storage and virtual machines for hosting critical services.
   - Secure connectivity established with AWS cloud via SEACOM ISP.

5. **Wireless Infrastructure:**
   - Cisco Wireless LAN Controllers (WLC) deployed for managing access points.
   - Segmentation for wired and wireless users.

6. **Voice and Communication:**
   - Cisco voice gateway to support enterprise communication needs.

## Future Enhancements
- Deployment of additional redundancy in the DMZ zone.
- Implementation of SD-WAN for optimized cloud connectivity.
- Integration of monitoring tools for network performance.

## Acknowledgments
- This project was developed as part of the Advanced Enterprise Networking course.
- Special thanks to Roles Tech for providing the opportunity to work on this project.
