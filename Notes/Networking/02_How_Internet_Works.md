# How the Internet Works

## Introduction

The Internet is a global network of interconnected computers that communicate using the TCP/IP protocol suite. When a user opens a website, several networking components work together to deliver the requested webpage.

---

# Components of the Internet

## 1. IP Address

An IP (Internet Protocol) Address is a unique identifier assigned to every device connected to a network.

### Example

```text
192.168.1.10
```

### Purpose

* Identifies devices on a network.
* Enables communication between devices.
* Works like a postal address for computers.

---

## 2. Switch

A switch is a networking device that connects multiple devices within the same Local Area Network (LAN).

### Functions

* Receives data frames.
* Uses MAC addresses to determine the destination.
* Sends data only to the intended device.

### OSI Layer

Layer 2 – Data Link Layer

### Example

In a computer lab, a switch connects multiple computers within the same network.

---

## 3. Router

A router is a networking device that connects different networks together.

### Functions

* Routes packets between networks.
* Determines the best path for data transmission.
* Connects local networks to the Internet.

### OSI Layer

Layer 3 – Network Layer

### Example

A home Wi-Fi router connects devices in the house to the Internet through an ISP.

---

## 4. DNS (Domain Name System)

DNS converts human-readable domain names into IP addresses.

### Example

```text
www.google.com
```

is converted into

```text
142.250.xxx.xxx
```

### Purpose

Humans remember names, while computers communicate using IP addresses.

DNS acts as the phonebook of the Internet.

---

# How a Website Loads

Suppose a user enters:

```text
www.google.com
```

into a web browser.

---

## Step 1: User Sends Request

The browser receives the website name.

```text
User → Browser
```

---

## Step 2: DNS Lookup

The browser asks a DNS server:

```text
What is the IP address of www.google.com?
```

DNS returns the IP address.

```text
Browser → DNS → IP Address
```

---

## Step 3: Packet Creation

The browser creates data packets.

Packet switching divides information into small packets for efficient transmission.

```text
Packet 1
Packet 2
Packet 3
Packet 4
```

---

## Step 4: Switch Forwards Data

Inside the local network, the switch forwards the data to the appropriate device.

```text
Computer → Switch
```

---

## Step 5: Router Routes Packets

The router receives the packets and forwards them toward the destination network.

```text
Switch → Router
```

The router selects the best path for packet delivery.

---

## Step 6: ISP Connection

The router sends packets to the Internet Service Provider (ISP).

Examples:

* Jio
* Airtel
* BSNL

```text
Router → ISP
```

---

## Step 7: Server Receives Request

Google's server receives the request.

```text
ISP → Internet → Google Server
```

---

## Step 8: Server Sends Response

The server processes the request and sends back:

* HTML
* CSS
* JavaScript
* Images

The response is again divided into packets.

---

## Step 9: Browser Displays Webpage

The browser reassembles all packets and displays the webpage.

```text
Google Server
↓
Internet
↓
ISP
↓
Router
↓
Switch
↓
Computer
↓
Browser
↓
Webpage Displayed
```

---

# Complete Flow

```text
User
↓
Browser
↓
DNS
↓
IP Address
↓
Switch
↓
Router
↓
ISP
↓
Internet
↓
Server
↓
Response
↓
Browser
↓
Webpage
```

---

# Summary

* IP Address uniquely identifies devices.
* Switch connects devices within a local network.
* Router connects different networks.
* DNS converts domain names into IP addresses.
* Packet switching divides data into small packets.
* Servers provide requested resources.
* Browsers display the received content.

The Internet works through cooperation between switches, routers, DNS servers, ISPs, and web servers using the TCP/IP protocol suite.
