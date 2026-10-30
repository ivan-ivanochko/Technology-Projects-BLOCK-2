
## 🧠 6. Reflection

Answer in full sentences:

1. What are the advantages of DHCP over static IP assignment?  
DHCP assigns IP addresses automatically, so administrators do not have to configure every device by hand. This saves time, especially in large networks, and reduces human errors such as typing a wrong address or accidentally giving two devices the same IP. DHCP also makes it easy to change network settings centrally, because the server can hand out the subnet mask, default gateway, and DNS server along with the address. In addition, addresses are reused when devices leave the network, which uses the available address pool efficiently.

2. How does DNS improve usability in a network?  
DNS translates human-friendly names, like www.example.com, into IP addresses, so users do not have to remember long numbers. It also means that a server’s IP address can change without users noticing, because the name stays the same. This makes the network easier to use, manage, and scale.
3. What would happen if the DHCP server went offline?  
Devices that already have an IP address would usually keep working until their lease expires, after which they could no longer renew it. New devices joining the network would not receive an IP address, so they could not communicate. Many operating systems would assign themselves an automatic private address (APIPA, in the 169.254.x.x range), which only allows communication with other devices on the same local network and not with the wider network or the internet.
4. Optional: What part of this activity did you find easy or challenging? Why?
I found the basic concepts, such as understanding what a switch does and what DHCP and DNS are for, fairly easy because they are logical and can be seen working in Packet Tracer. The more challenging part was subnetting and the CLI commands, because they require remembering exact syntax and understanding how the bits of an IP address and mask relate to each other. With practice and repeated labs, I expect these to become easier.
