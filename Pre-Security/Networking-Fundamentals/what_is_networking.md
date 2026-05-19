# What is Networking?  

##  Basics  
- A **network** is simply 2 or more devices connected together.  
- The **Internet** is a giant network made up of smaller networks connected together.  

---

##  Public Network  
- Openly accessible to anyone.  
- Devices connected here are exposed to the internet.  
- Uses **public IP addresses**.  
- **Examples:** Internet, Café Wi-Fi.  

##  Private Network  
- Restricted, only accessible by authorized users/devices.  
- Found in homes, offices, organizations.  
- Uses **private IP addresses**.  
- **Examples:** Home Wi-Fi, Company LAN.  

---

##  Identifying Devices on a Network  

### IP Address ( Fingerprint)  
- Consists of **4 octets** in IPv4.  
- Unique per device (cannot be the same on two devices in the same network).  
- **Public IP**: Identifies device on the internet (assigned by ISP).  
- **Private IP**: Identifies device inside the local network.  
- **IPv4**: 32 bits → 2³² addresses.  
- **IPv6**: 128 bits → 2¹²⁸ addresses.  
  - Written as 8 groups of 4 hexadecimal digits.  
  - 1 hex digit = 4 bits → 32 hex digits in total.  

### MAC Address (Name)  
- **Permanent** address tied to the device’s network interface.  
- 12 hexadecimal characters (6 bytes = 48 bits).  
- Example: `00:1A:2B:3C:4D:5E`.  
- Can be **spoofed** (faking another device’s MAC).  

---

##  Firewalls  
- Security tool to filter network traffic.  
- Blocks unauthorized incoming/outgoing traffic.  
- Two types: **Hardware Firewall** & **Software Firewall**.  

---

##  Ping  
- Uses **ICMP (Internet Control Message Protocol)**.  
- Tests connection performance between two devices.  
- Sends ICMP **echo request** and receives **echo reply**.  
- Can use an **IP address or URL**.  
- Firewalls may block ICMP even if the network is working.  
