# Routing & Remote Connectivity Tools

These tools are used to **test routing configurations**, measure **connectivity**, and troubleshoot paths to remote hosts and networks.

---

## 🛣️ route
View and configure the host's **local routing table**.
- Most end systems rely on a **default route** to forward all traffic destined for remote networks via a gateway router.
**Example:**
```cmd
route print     # Windows
route -n        # Linux
```

## tracert (Windows)
- Uses ICMP probes to display the round-trip time (RTT) for each hop between the local machine and a remote host.
**Example:**
```cmd
tracert google.com
```

## 🛰️ traceroute (Linux)
- Performs route discovery on Linux systems.
- Uses UDP probes by default (not ICMP like Windows).
**Example:**
```cmd
traceroute google.com
```

## 📊 pathping (Windows)
- Combines the functions of ping and tracert.
- Provides statistics on latency and packet loss over a longer measurement period.
**Example:**
```cmd
pathping google.com
```
