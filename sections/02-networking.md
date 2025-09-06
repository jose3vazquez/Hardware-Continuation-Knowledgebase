# 02. Networking (Logical & Protocol Layer) (60 Facts)

### TCP/IP Fundamentals
1. The TCP/IP model has 4 layers: Application, Transport, Internet, Network Access. *(A+ 220-1101, Obj 2.1)*  
2. IPv4 addresses are 32-bit, written in dotted decimal format. *(2.1)*  
3. IPv6 addresses are 128-bit, written in hexadecimal with colons. *(2.1)*  
4. Private IPv4 ranges include 10.0.0.0/8, 172.16–31.0.0/16, and 192.168.0.0/16. *(2.1)*  
5. APIPA assigns automatic addresses in the 169.254.0.0/16 range. *(2.1)*  
6. Subnet masks divide IP ranges into networks and hosts. *(2.1)*  
7. CIDR notation expresses subnet size using a slash (e.g., /24 = 255.255.255.0). *(2.1)*  
8. Default gateways forward packets between local and remote networks. *(2.1)*  
9. NAT (Network Address Translation) maps private to public IP addresses. *(2.2)*  
10. PAT (Port Address Translation) allows multiple devices to share one public IP. *(2.2)*  

### Ports & Protocols
11. HTTP uses port 80 (unencrypted web traffic). *(2.2)*  
12. HTTPS uses port 443 with SSL/TLS encryption. *(2.2)*  
13. FTP uses ports 20/21 for file transfer. *(2.2)*  
14. SFTP (Secure FTP) uses SSH over port 22. *(2.2)*  
15. SMTP uses port 25 (sending mail). *(2.2)*  
16. POP3 uses port 110 (retrieving mail). *(2.2)*  
17. IMAP uses port 143 (retrieving mail with sync). *(2.2)*  
18. RDP uses port 3389 for remote desktop access. *(2.2)*  
19. SSH uses port 22 for secure remote login. *(2.2)*  
20. DNS uses port 53 for name resolution. *(2.2)*  

### Wireless Standards & Encryption
21. 802.11a operates at 5 GHz, max 54 Mbps. *(2.4)*  
22. 802.11b operates at 2.4 GHz, max 11 Mbps. *(2.4)*  
23. 802.11g operates at 2.4 GHz, max 54 Mbps. *(2.4)*  
24. 802.11n operates at 2.4/5 GHz, supports MIMO, max 600 Mbps. *(2.4)*  
25. 802.11ac operates at 5 GHz, supports MU-MIMO, multi-Gbps. *(2.4)*  
26. 802.11ax (Wi-Fi 6) supports OFDMA and target wake time, multi-Gbps. *(2.4)*  
27. WEP is outdated and insecure. *(2.4)*  
28. WPA replaced WEP but was quickly deprecated. *(2.4)*  
29. WPA2 uses AES and CCMP for secure encryption. *(2.4)*  
30. WPA3 introduces individualized encryption and improved handshake security. *(2.4)*  

### SOHO Networks
31. SOHO routers typically combine modem, router, switch, and wireless AP. *(2.3)*  
32. DHCP automatically assigns IP addresses in SOHO networks. *(2.3)*  
33. Port forwarding directs external traffic to internal devices. *(2.3)*  
34. Port triggering dynamically opens ports when outbound traffic occurs. *(2.3)*  
35. DMZ exposes a device to the internet with minimal firewall protection. *(2.3)*  
36. QoS prioritizes certain types of network traffic (e.g., VoIP). *(2.3)*  
37. MAC filtering allows or denies devices based on MAC addresses. *(2.3)*  
38. SSID broadcast can be disabled for obscurity, but it’s not secure. *(2.3)*  
39. UPnP automatically configures port forwarding for devices and apps. *(2.3)*  
40. Guest networks isolate visitors from the main LAN. *(2.3)*  

### DNS, DHCP, VPN & Services
41. DNS translates hostnames to IP addresses. *(2.2)*  
42. DNS record types: A (IPv4), AAAA (IPv6), MX (mail), CNAME (alias). *(2.2)*  
43. DHCP lease time defines how long a device keeps its assigned IP. *(2.2)*  
44. DHCP reservations ensure a device always gets the same IP. *(2.2)*  
45. VPNs create secure encrypted tunnels between endpoints. *(2.2)*  
46. PPTP is an older VPN protocol with weak security. *(2.2)*  
47. L2TP/IPsec offers stronger VPN encryption. *(2.2)*  
48. SSL/TLS VPNs use HTTPS for secure remote access. *(2.2)*  
49. Always-On VPN reconnects automatically after disruptions. *(2.2)*  
50. Split tunneling routes only some traffic through the VPN. *(2.2)*  

### Network Tools & Troubleshooting
51. `ping` checks host reachability via ICMP. *(2.5)*  
52. `tracert` (Windows) / `traceroute` (Linux/macOS) maps the route to a host. *(2.5)*  
53. `nslookup` and `dig` query DNS records. *(2.5)*  
54. `ipconfig /all` displays full network adapter configuration. *(2.5)*  
55. `ifconfig` or `ip addr` shows IP info in Linux/macOS. *(2.5)*  
56. `netstat -an` shows active connections and listening ports. *(2.5)*  
57. `arp -a` displays MAC-to-IP mappings. *(2.5)*  
58. `tcpdump` captures live packet data. *(2.5)*  
59. `nmap` scans for open ports and services. *(2.5)*  
60. `pathping` (Windows) combines ping and traceroute functionality. *(2.5)*  

---