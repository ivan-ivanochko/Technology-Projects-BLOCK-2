## 🧠 5. Reflection Questions

### 5.1 What would happen if two PCs had the same IP address?

An IP address conflict occurs. Both computers will have trouble communicating on the network: packets sent to that IP may reach one PC or the other unpredictably, so connections drop or work unreliably. The operating system usually shows an “IP address conflict” warning.

### 5.2 Why do we use a switch instead of directly connecting PCs together?

A direct connection only works for two PCs (or you would need a separate network card for every link). A switch lets many devices connect through a single device, and it forwards frames using MAC addresses only to the intended recipient. This scales easily, costs less, and reduces unnecessary traffic.

### 5.3 What does the subnet mask 255.255.255.0 indicate?

It shows which part of an IP address identifies the network and which part identifies the host. The mask 255.255.255.0 (also written /24) means the first three octets (24 bits) are the network address, and the last octet (8 bits) is for devices. So the network supports up to 254 hosts (.1 to .254; .0 is the network address and .255 is the broadcast address). For example, 192.168.1.10 and 192.168.1.20 are on the same network, while 192.168.2.10 is on a different one.

