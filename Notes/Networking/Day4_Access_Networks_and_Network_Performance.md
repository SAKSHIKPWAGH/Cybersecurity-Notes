# Day 4: Access Networks, ISP Architecture, and Network Performance

## Access Networks

An **Access Network** is the part of the network that connects end users (homes, offices, or mobile devices) to the Internet.

### Types of Home Access Networks

#### DSL (Digital Subscriber Line)

* Uses existing telephone lines for Internet access.
* Provides broadband connectivity.
* Suitable for homes and small offices.

#### FTTH (Fiber to the Home)

* Uses optical fiber cables directly to the user's home.
* Offers very high-speed Internet.
* More reliable than DSL.

#### Cable Internet

* Uses cable TV infrastructure for Internet access.
* Provides high-speed broadband services.

#### Dial-Up

* Uses telephone lines and a modem.
* Very slow compared to modern broadband technologies.

#### Satellite Internet

* Uses communication satellites.
* Suitable for remote areas where wired connections are unavailable.

---

## Enterprise and Home Access Networks

### Ethernet

* Commonly used in Local Area Networks (LANs).
* Provides wired network connectivity.
* Typical user access speed: **100 Mbps**.
* Servers may have **1 Gbps** or **10 Gbps** connections.

### Wi-Fi

* Provides wireless network connectivity.
* Used in homes, schools, and offices.
* Covers a Local Area Network (LAN) within a short distance.

---

## Wide Area Wireless Access

Mobile Internet technologies include:

* **3G**
* **4G**
* **5G**

These technologies provide Internet access over cellular networks.

---

# A Network of Networks (ISP Hierarchy)

The Internet is formed by connecting multiple Internet Service Providers (ISPs).

### Types of ISPs

* **Access ISP** – Provides Internet service directly to customers.
* **Regional ISP** – Connects multiple Access ISPs within a region.
* **Global Transit ISP (Tier-1 ISP)** – Provides global Internet connectivity and connects Regional ISPs.

---

# Delay, Loss, and Throughput in Packet-Switched Networks

## Types of Delay

### 1. Processing Delay

Time taken by a router to examine the packet header and determine the forwarding path.

---

### 2. Queuing Delay

Time a packet waits in the router's queue before transmission.

---

### 3. Transmission Delay

Time required to transmit all bits of a packet onto the communication link.

**Formula:**

```text
Transmission Delay = L / R
```

Where:

* **L** = Packet Length (bits)
* **R** = Transmission Rate (bits/second)

---

### 4. Propagation Delay

Time taken for the signal to travel through the physical communication medium from sender to receiver.

---

# Total Nodal Delay

The total delay experienced by a packet at a router is:

```text
Dnodal = Dproc + Dqueue + Dtrans + Dprop
```

Where:

* **Dproc** = Processing Delay
* **Dqueue** = Queuing Delay
* **Dtrans** = Transmission Delay
* **Dprop** = Propagation Delay

---

# Packet Loss

Packet loss occurs when a packet arrives at a router whose queue is already full.

### Causes

* Limited queue capacity
* Network congestion
* High traffic intensity

When the queue overflows, incoming packets are discarded.

---

# Summary

* Access networks connect users to the Internet using technologies such as DSL, FTTH, Cable, Wi-Fi, and Ethernet.
* ISPs are organized into Access, Regional, and Tier-1 (Global Transit) providers.
* Network performance depends on four types of delay: Processing, Queuing, Transmission, and Propagation.
* Total packet delay is the sum of all four delays.
* Packet loss occurs when router queues become full due to heavy network traffic.
