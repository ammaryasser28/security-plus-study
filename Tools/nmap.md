# Network Scanning & Topology Discovery Tools

Network scanning is essential for identifying hosts, mapping network structures, and discovering running services.

---

## 🔍 Limitations of Basic Scanning (ping)
Using basic tools like `ping` for network scanning is:

- **Time-consuming**
- **Non-stealthy**
- Provides **limited and non-detailed information**

Because of this, dedicated IP scanners are preferred.

---

## 🚀 Dedicated IP Scanners
A **dedicated IP scanner** automates:

- Host discovery  
- Mapping how hosts are connected in an internetwork  

One of the most powerful scanners is:

---

## 🛡️ Nmap Security Scanner
**Nmap (nmap.org)** is a widely-used **open-source** tool for:

- Host discovery  
- Port scanning  
- Service and version detection  
- Stealthy reconnaissance  

### ✔ Features
- Works on **Windows, Linux, and macOS**  
- Can be used via:
  - **Command Line**
  - **Zenmap** GUI  
- Supports **stealth scanning methods** that can evade:
  - Firewalls  
  - Intrusion Detection Systems (IDS)

---

## 🧪 Nmap Basic Operation

### **Basic Syntax**
```bash
nmap <target>
```
Where <target> is an IP address or subnet (e.g., 192.168.1.0/24).

## Default Behavior
When run without switches:
- Sends ICMP ping
- Sends TCP ACK probes to ports 80 and 443
On local networks, also performs:
- ARP sweeps
- ND (Neighbor Discovery) sweeps (for IPv6)
