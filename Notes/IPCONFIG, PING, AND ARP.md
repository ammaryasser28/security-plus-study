# Network Reconnaissance & Discovery

Network reconnaissance and discovery refers to the **process of mapping out the attack surface**.  
These techniques are used by both **threat actors** and **security professionals** during assessments and monitoring.

---

## 🔍 Topology Discovery (Footprinting)

Topology discovery means scanning for:

- Hosts  
- IP ranges  
- Network routes  

This helps map the structure of the target network.

**Uses:**

- Building an asset database  
- Detecting unauthorized/rogue systems  
- Identifying misconfigurations  

---

## 🛠️ Basic Topology Discovery Tools (Windows & Linux)

These command-line tools help report IP configuration and test connectivity within a local subnet.

### **ipconfig (Windows)**
Shows network interface configuration.  
```cmd
ipconfig
```
### **ifconfig (Linux)**
Shows assigned network configuration.
```cmd
ifconfig
```
### **ping**
- Uses ICMP to probe a host by IP or hostname.
- Can be scripted to sweep an entire subnet.
```cmd
ping 192.168.1.1
```
### **arp**
Displays the ARP cache, showing MAC addresses recently communicated with.
```cmd
arp -a
```
