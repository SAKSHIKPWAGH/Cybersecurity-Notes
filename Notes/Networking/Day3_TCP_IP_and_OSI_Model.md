# Day 3: TCP/IP Model and OSI Model

## TCP/IP Model

The **TCP/IP (Transmission Control Protocol/Internet Protocol)** model is the standard networking model used for communication over the Internet. It consists of **five layers**, where each layer performs a specific function and uses different protocols.

---

## 1. Physical Layer

### Function

The Physical Layer is responsible for transmitting individual bits from one device to another through a physical medium.

### Common Technologies

* Twisted Pair Copper Wire
* Coaxial Cable
* Fiber Optic Cable

---

## 2. Link Layer

### Function

The Link Layer transfers data between two directly connected devices. It packages data into **frames** and works with the Network Layer to forward packets.

### Packet Unit

**Frame**

### Common Protocols

* Ethernet
* Wi-Fi (IEEE 802.11)
* DOCSIS (Cable Access Network)

---

## 3. Network Layer

### Function

The Network Layer is responsible for routing data (datagrams) from the source host to the destination host through multiple routers.

### Packet Unit

**Datagram (Packet)**

### Common Protocols

* IP (Internet Protocol)
* ICMP (Internet Control Message Protocol)
* Routing Protocols

---

## 4. Transport Layer

### Function

The Transport Layer delivers application data between end devices and provides reliable or unreliable communication.

### Packet Unit

**Segment**

### Common Protocols

* TCP (Transmission Control Protocol)
* UDP (User Datagram Protocol)

### Services

* Connection-Oriented Communication (TCP)
* Connectionless Communication (UDP)

---

## 5. Application Layer

### Function

The Application Layer provides network services directly to user applications.

### Packet Unit

**Message**

### Common Protocols

* HTTP
* SMTP
* FTP
* DNS

---

# TCP/IP Protocol Stack

| Layer       | Common Protocols                          |
| ----------- | ----------------------------------------- |
| Application | HTTP, SMTP, RTP, DNS                      |
| Transport   | TCP, UDP                                  |
| Internet    | IP, ICMP                                  |
| Link        | Ethernet, IEEE 802.11 (Wi-Fi), DSL, SONET |

---

# Encapsulation

Encapsulation is the process of adding protocol-specific information (headers) to data as it moves down the TCP/IP layers before transmission.

### Process

```text
Application Message
        ↓
Transport Layer → Segment
        ↓
Network Layer → Packet (Datagram)
        ↓
Link Layer → Frame
        ↓
Physical Layer → Bits
```

At the receiving host, the reverse process is called **Decapsulation**, where each layer removes its corresponding header to recover the original message.

---

# OSI Model

The **OSI (Open Systems Interconnection)** model is a seven-layer reference model used to understand network communication.

| Layer        | Unit Exchanged |
| ------------ | -------------- |
| Application  | APDU           |
| Presentation | PPDU           |
| Session      | SPDU           |
| Transport    | TPDU           |
| Network      | Packet         |
| Data Link    | Frame          |
| Physical     | Bit            |

---

# Core Concepts of the OSI Model

1. **Services** – Functions provided by a layer to the layer above it.
2. **Interfaces** – Define how adjacent layers communicate.
3. **Protocols** – Rules that govern communication between devices at the same layer.

---

# Why the OSI Model Failed

The OSI model was not widely adopted due to:

* Bad Timing
* Complex Design
* Poor Implementation
* Political Issues among standardization organizations

---

# OSI vs TCP/IP

| OSI Model          | TCP/IP Model             |
| ------------------ | ------------------------ |
| 7 Layers           | 5 Layers                 |
| Reference Model    | Practical Internet Model |
| More Complex       | Simpler and Widely Used  |
| Mostly Educational | Used in Real Networks    |
| Developed by ISO   | Developed by DARPA       |

---

# Summary

* The TCP/IP model consists of five layers used for Internet communication.
* Each layer has specific responsibilities and protocols.
* Encapsulation adds headers to data as it moves through the layers.
* The OSI model is a seven-layer conceptual model used to understand networking.
* TCP/IP is the practical networking model used worldwide.
