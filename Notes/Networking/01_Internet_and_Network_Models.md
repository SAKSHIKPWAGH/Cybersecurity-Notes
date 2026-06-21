# Internet and Network Models

## History of the Internet

### 1960 - Early Networking Ideas

Researchers started exploring ways for computers to communicate and share information over long distances.

### 1969 - ARPANET

ARPANET (Advanced Research Projects Agency Network) was the first operational packet-switching network and is considered the foundation of the modern Internet.

### Packet Switching

Packet switching is a method of transmitting data in small packets across a network. Each packet may travel through different paths before reaching its destination.

**Advantages:**

* Efficient bandwidth usage
* Reliable communication
* Scalable networking

---

# Network Models

Network models provide a structured framework for communication between devices.

## 1. TCP/IP Model

The TCP/IP model is the standard model used on the Internet.

### Layers of TCP/IP Model

### Application Layer

Provides services directly to users and applications.

**Examples:**

* HTTP
* HTTPS
* FTP
* SMTP
* DNS

### Transport Layer

Responsible for end-to-end communication and data delivery.

**Protocols:**

* TCP (Transmission Control Protocol)
* UDP (User Datagram Protocol)

### Network Layer

Handles routing and logical addressing.

**Protocol:**

* IP (Internet Protocol)

### Data Link Layer

Responsible for communication between devices on the same network.

**Devices:**

* Switches

### Physical Layer

Responsible for transmitting raw bits through physical media.

**Devices:**

* Cables
* Wireless Access Points (WAP)

---

# 2. OSI Model

The OSI (Open Systems Interconnection) model consists of seven layers.

### Layer 7 - Application Layer

Provides network services to applications.

### Layer 6 - Presentation Layer

Handles data formatting, encryption, and compression.

### Layer 5 - Session Layer

Manages communication sessions between systems.

### Layer 4 - Transport Layer

Ensures reliable data transfer.

### Layer 3 - Network Layer

Responsible for routing packets.

**Device:**

* Router

### Layer 2 - Data Link Layer

Responsible for frame transmission and MAC addressing.

**Device:**

* Switch

### Layer 1 - Physical Layer

Responsible for transmitting bits over physical media.

**Examples:**

* Network Cables
* Wireless Access Points (WAP)

---

# Key Difference Between TCP/IP and OSI

| TCP/IP Model             | OSI Model          |
| ------------------------ | ------------------ |
| 5 Layers                 | 7 Layers           |
| Practical Implementation | Reference Model    |
| Used on the Internet     | Mainly Educational |
| Developed by DoD         | Developed by ISO   |

---

## Summary

* ARPANET was the foundation of the Internet.
* Packet switching is the core communication method used in networks.
* TCP/IP is the practical Internet model.
* OSI is a conceptual networking model.
* Routers operate at Layer 3.
* Switches operate at Layer 2.
* Physical devices operate at Layer 1.
