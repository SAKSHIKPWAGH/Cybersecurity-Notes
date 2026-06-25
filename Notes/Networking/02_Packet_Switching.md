# Network Core

The network core consists of interconnected routers and switches that transport data between end systems.

Two fundamental approaches are used to move data through a network of links and switches:

1. Packet Switching
2. Circuit Switching

---

# 1. Packet Switching

## Packet

To send a message from a source to a destination, a large message is divided into smaller units called **packets**.

Example:

A 10 MB file is broken into many small packets before transmission.

---

## Store-and-Forward Transmission

In packet-switched networks, a router or switch must receive the entire packet before forwarding it to the next device.

Example:

Source → Router → Destination

The router receives the complete packet and then forwards it.

---

## Queuing Delay and Packet Loss

When many packets arrive at a router simultaneously:

* Packets wait in a queue.
* Waiting causes **queuing delay**.
* If the queue becomes full, packets are dropped, resulting in **packet loss**.

---

## Forwarding Tables and Routing Protocols

Routers use:

* Forwarding Tables
* Routing Protocols

to determine the best path for packets to reach their destination.

Examples of routing protocols:

* RIP
* OSPF
* BGP

---

# 2. Circuit Switching

In a circuit-switched network, resources are reserved along the communication path before data transfer begins.

The reserved resources remain dedicated for the entire communication session.

Example:

Traditional telephone networks.

---

# Packet Switching vs Circuit Switching

## Advantages of Packet Switching

1. Better utilization and sharing of network resources.
2. More efficient than circuit switching.
3. Lower implementation cost.
4. Supports a large number of users simultaneously.
5. Forms the basis of the modern Internet.

## Advantages of Circuit Switching

1. Dedicated communication path.
2. Predictable performance.
3. Consistent bandwidth during communication.

---

# Conclusion

Modern computer networks and the Internet primarily use packet switching because it provides efficient resource utilization, scalability, and lower operational cost.
