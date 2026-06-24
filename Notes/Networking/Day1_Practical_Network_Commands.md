# Day 1 Practical: Basic Network Commands

## Objective

To understand basic networking concepts and verify Internet connectivity using Command Prompt commands.

---

## 1. Ping Test

### Command

```cmd
ping google.com
```

### Observation

* Google server responded successfully.
* Packets Sent: 4
* Packets Received: 4
* Packet Loss: 0%
* Average Response Time: 8 ms

### Result

Internet connection is working properly and communication with Google's server was successful.

---

### Command

```cmd
ping youtube.com
```

### Observation

* YouTube server responded successfully.
* Packets Sent: 4
* Packets Received: 4
* Packet Loss: 0%
* Average Response Time: 8 ms

### Result

Network connectivity to YouTube was verified successfully.

---

## 2. IP Configuration

### Command

```cmd
ipconfig
```

### Important Information Obtained

| Parameter       | Value         |
| --------------- | ------------- |
| IPv4 Address    | 172.16.16.46  |
| Subnet Mask     | 255.255.252.0 |
| Default Gateway | 172.16.16.1   |

### Result

Successfully identified the system's IP address, subnet mask, and default gateway.

---

## 3. Trace Route

### Command

```cmd
tracert google.com
```

### Observation

* The route to Google's server was traced through multiple routers.
* Some intermediate routers showed "Request timed out".
* Final hops successfully reached Google's network.

### Result

The path taken by packets from the local system to Google's server was successfully analyzed.

---

## Conclusion

During this practical session, the following networking commands were executed:

1. `ping` – Tested Internet connectivity and response time.
2. `ipconfig` – Displayed network configuration details.
3. `tracert` – Traced the route taken by packets to reach a destination server.

The practical helped in understanding basic network diagnostics and Internet communication.
