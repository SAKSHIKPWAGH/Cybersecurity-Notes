# Day 2 Practical: Packet Switching

## Practical 1: Internet Speed Test

### Objective

To measure Internet performance using Speedtest.

### Procedure

1. Open https://www.speedtest.net
2. Click **GO**.
3. Wait for the test to complete.
4. Record Download Speed, Upload Speed, and Ping.

### Observations

| Parameter      | Value       |
| -------------- | ----------- |
| Download Speed | 55.78 Mbps  |
| Upload Speed   | 256.62 Mbps |
| Ping           | 34 ms       |

### Screenshot

![Speed Test](screenshots/practical1_screenshot.png)

### Result

The Internet connection was successfully tested and network performance metrics were recorded.

---

## Practical 2: Webpage Request Analysis

### Objective

To observe network requests generated while loading a webpage.

### Procedure

1. Open Google Chrome.
2. Press **F12** to open Developer Tools.
3. Go to the **Network** tab.
4. Open **google.com**.
5. Observe the generated requests.

### Observations

* Multiple requests were generated while loading the webpage.
* Resources such as HTML, CSS, JavaScript, images, and API requests were loaded.
* A single webpage consists of multiple packets/resources.

### Screenshot

![Webpage Requests](screenshots/webpage_request.png)

### Result

Observed that a webpage is loaded through multiple network requests, demonstrating packet-switched communication.

---

## Practical 3: Network Communication Flow

### Objective

To understand the path followed by data packets from a client to a server.

### Diagram

```text
Laptop
   ↓
Router
   ↓
ISP
   ↓
Internet
   ↓
Google Server
```

### Result

Understood the communication flow between a client device and a web server through the Internet.

---

## Conclusion

Successfully performed Internet speed testing, analyzed webpage network requests using browser developer tools, and understood the basic communication path in a packet-switched network.
