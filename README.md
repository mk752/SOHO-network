# SOHO Network Build 
Small office / home office network built : VLANS, DHCP, Router on a stick, NAT, WPA2 Wireless

## Features Implemented
- 2 switches with VLAN 10 (Employees) & VLAN 20 (Wireless)
- Router-on-a-stick inter-VLAN routing
- DHCP pools for both VLANs
- NAT/PAT + default route to simulated Internet
- Static IP printer
- Wireless AP with WPA2-PSK SSID "SOHO-Office"
- Full connectivity (PC ↔ Printer ↔ Wireless ↔ Internet)

## Topology
![Topology](topology.png)

## Skills Demonstrated
- VLANs & trunking
- DHCP configuration
- Routing & NAT overload
- Wireless security
- Device cabling (Straight-Through)

Built and tested in Cisco Packet Tracer.  
All core requirements met (even if Cloud-PT internet ping is still being tweaked — NAT translations confirmed working).

Files included:  
- Full .pkt project file  
- Running configs  
- All test screenshots
