# Network Design and Implementation
I designed and created a network for a made up company by the name of 'SAFEBI'.
This was a project I did at university which integrated the key concepts covered in our Networking module.

# Features
- Extended Star Topology
- Small level of redundancy (3 routers)
- Router-on-a-Stick configuration for each floor
- OSPF (Open Shortest Path First) routing protocol
- Variable Length Subnetting
- Department specific VLANs
- Trunking to enable communication between VLANs
- A DHCP server to dynamically allocate IP addresses
- HTTP, DNS, and E-mail servers in the Server Room
- Wireless Access Points in each department
- SSH on routers
- MotD banners warning unauthorised access

# How to open the file
Open 'SAFEBI.pkt' in Cisco Packet Tracer
which can be downloaded from ![Cisco's NetAcademy](https://www.netacad.com/cisco-packet-tracer)

Note: It may take a few minutes to start up once opened.

# Passwords Used
Each router and switch has been set up with a temporary password to secure its CLI, these are all encrypted and stored in the startup-config of each device.
To deter brute force attacks, 5 incorrect password attempts (made within 2 minutes) will lock the CLI for 3 minutes, and lock Privileged Execution mode for 6 minutes.
Wireless Access Points have been set up using WPA2-2SK security.

| Device | Password |
| ------------- | ------------- |
| Router  | SAFEBIrouter1  |
| Switch  | SAFEBIswitch1  |
| Wireless Access Point  | SAFEBIaccess1  |
| SSH Username | SAFEBIuser1 |
| SSH Password | SAFEBIpass1 |
| Privileged Execution on any router / switch | SAFEBIenable1  |
