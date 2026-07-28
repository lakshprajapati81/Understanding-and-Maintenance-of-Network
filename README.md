# Computer Networking Hardware Assignment

---
DAY 1 :- Introduction To Networking Hardware 
---

# Task 1 - Home Wi-Fi Network Diagram

## Labeled Home Wi-Fi Network

![Home Wi-Fi Network Diagram](/home-network-diagram.png)

---

## Network Explanation

A typical home network begins with the Internet Service Provider (ISP) delivering an internet connection to the modem. The modem converts the ISP signal into Ethernet data. The router receives this connection and performs routing, DHCP, NAT, firewall protection, and Wi-Fi services. A network switch expands the number of Ethernet ports, allowing multiple wired devices to communicate efficiently. An access point extends wireless coverage so mobile devices can connect from different locations within the home.

---

# Task 2 - Networking Hardware Devices

| Device | Main Function | Real-Life Example |
|---------|---------------|------------------|
| Modem | Converts ISP signal into digital Ethernet signal | Installed by JioFiber, Airtel Xstream, or BSNL Fiber at home |
| Router | Connects different networks and shares internet | Home Wi-Fi Router |
| Switch | Connects multiple wired devices in a Local Area Network | Computer Lab or Office |
| Access Point | Provides wireless network access and extends Wi-Fi coverage | School, Hotel, Airport |
| Network Cable | Transfers data between networking devices | Connecting a PC to a Router |

---

## 1. Modem

### Function

- Connects the ISP network to your home.
- Converts fiber, DSL, or cable signals into Ethernet.
- Provides internet access to the router.

### Real-Life Example

A modem installed by JioFiber inside a home.

**Image**

![Modem](/modem.jpg)

---

## 2. Router

### Function

- Connects different networks.
- Shares internet with multiple devices.
- Performs NAT.
- Assigns IP addresses using DHCP.
- Provides Wi-Fi.
- Protects the network with a firewall.

### Real-Life Example

TP-Link, ASUS, D-Link, or Netgear Wi-Fi router used at home.

**Image**

![Router](/router.jpg)

---

## 3. Switch

### Function

- Connects multiple wired devices.
- Uses MAC addresses for forwarding.
- Reduces unnecessary network traffic.
- Provides high-speed communication inside a LAN.

### Real-Life Example

Office network connecting multiple desktop computers.

**Image**

![Network Switch](/network-switch.jpg)

---

## 4. Access Point

### Function

- Creates wireless connectivity.
- Extends Wi-Fi coverage.
- Allows smartphones and laptops to connect wirelessly.

### Real-Life Example

Wi-Fi access point installed in a college campus.

**Image**

![Wireless Access Point](/access-point.jpg)

---

## 5. Network Cable

### Function

- Transfers data between networking devices.
- Provides reliable wired communication.

### Real-Life Example

Ethernet cable connecting a desktop computer to a router.

**Image**

![Network Cable](/network-cable.jpg)

---

# Task 3 - Network Cable Types

## Ethernet Cable (Cat6)

![Ethernet Cable](/ethernet-cable.jpg)

**Common Use**

Used to connect computers, routers, switches, printers, gaming consoles, and smart TVs in homes and offices.

---

## Coaxial Cable

![Coaxial Cable](/coaxial-cable.jpg)

**Common Use**

Used for cable television and broadband internet connections.

---

## Fiber Optic Cable

![Fiber Optic Cable](/fiber-optic-cable.jpg)

**Common Use**

Used by Internet Service Providers for high-speed internet and long-distance communication.

---

## Cable Comparison

| Cable Type | Maximum Speed | Maximum Distance | Common Use |
|-------------|--------------|-----------------|------------|
| Ethernet (Cat6) | Up to 10 Gbps | 100 meters | Home and Office LAN |
| Coaxial | Up to 1 Gbps | 500 meters | Cable TV and Broadband |
| Fiber Optic | 100+ Gbps | More than 100 km | ISP Backbone and Data Centers |

---

# Task 4 - Router vs Switch Comparison

| Feature | Router | Switch |
|-----------|---------|---------|
| Main Purpose | Connects different networks | Connects devices within the same network |
| OSI Layer | Layer 3 (Network Layer) | Layer 2 (Data Link Layer) |
| Address Used | IP Address | MAC Address |
| Data Unit | Packet | Frame |
| Internet Sharing | Yes | No |
| DHCP Support | Yes | No |
| NAT Support | Yes | No |
| Firewall | Available | Not Available |
| Typical Location | Home Gateway, Office Gateway | Office LAN, Computer Labs |
| Number of Ports | Usually 4–8 | Usually 8–48 |
| Wireless Support | Yes | No |
| Broadcast Domain | Separates Broadcast Domains | Same Broadcast Domain |

---


DAY 2 :- Routers And Switches
---

# Task 1 – Labelled Diagram of a Home Wi-Fi Router and Network Switch

## Home Wi-Fi Router

![Home Wi-Fi Router](/router-diagram.jpg)

### Labels

- **Power Port** – Connects the router to the power adapter.
- **WAN Port** – Receives the internet connection from the modem/ISP.
- **LAN Ports (LAN1–LAN4)** – Connect desktops, switches, printers, etc.
- **Reset Button** – Restores factory settings.
- **Wi-Fi Antennas** – Broadcast wireless signals.
- **Status LEDs**
  - Power
  - Internet
  - WAN
  - LAN
  - Wi-Fi
  - WPS

---

## Network Switch

![Network Switch](/switch-diagram.jpg)

### Labels

- **Power Port** – Supplies electrical power.
- **Ethernet Ports (Port 1–8)** – Connect PCs, printers, and other devices.
- **Console Port** *(Managed Switch Only)* – Used for configuration and troubleshooting.
- **Status LEDs**
  - Power
  - Link/Activity
  - Speed
  - Port Status

---

# Task 2 – Router vs Switch (3 Key Differences)

| Feature | Router | Switch |
|---------|---------|---------|
| **Main Function** | Connects different networks (LAN to Internet). | Connects devices within the same Local Area Network (LAN). |
| **Address Used** | Uses **IP Addresses** to route packets between networks. | Uses **MAC Addresses** to forward data between local devices. |
| **Traffic Handling** | Routes packets between different networks using routing tables. | Forwards Ethernet frames only to the correct destination port using a MAC address table. |

---

# Task 3 – Router and Switch Identification


### Components Identified

| Component | Position | Purpose |
|------------|----------|----------|
| Power Port | Rear Left | Supplies power to the router. |
| WAN Port | Rear (Blue Port) | Connects the modem or ISP line. |
| LAN Port 1 | Rear (Yellow Port) | Connects a desktop computer or switch. |
| LAN Port 2 | Rear (Yellow Port) | Connects another wired device. |
| LED Indicators | Front Panel | Show Power, Internet, Wi-Fi, LAN activity, and system status. |

---


### Components Identified

| Component | Position | Purpose |
|------------|----------|----------|
| Power Port | Rear Side | Supplies electrical power. |
| Ethernet Port 1 | Front Panel | Connects the first computer. |
| Ethernet Port 2 | Front Panel | Connects another network device. |
| LED Indicators | Above Each Port | Display Link, Activity, and Speed status. |

---

# Task 4 – Gaming Café Network Scenario

## Scenario

A gaming café is being set up to provide **IPL live streaming** and **multiplayer online gaming** for customers. The café has a high-speed fiber internet connection provided by the ISP and contains **8 gaming PCs**, one billing computer, and one Wi-Fi access point.

### Network Setup

1. The **ISP fiber line** is first connected to the **modem**.
2. The modem is connected to the **router** through the **WAN port**.
3. The router provides:
   - Internet access
   - DHCP (automatic IP address assignment)
   - NAT (Network Address Translation)
   - Firewall protection
4. One LAN port of the router is connected to an **8-port Gigabit Network Switch**.
5. All **8 gaming PCs** are connected to the switch using Cat6 Ethernet cables.
6. The billing computer is also connected to the switch.
7. A wireless access point can be connected to the router or switch to provide Wi-Fi for customers.

### Network Diagram

```
Internet
    │
 ISP Fiber
    │
  Modem
    │
  Router
    │
8-Port Gigabit Switch
├── Gaming PC 1
├── Gaming PC 2
├── Gaming PC 3
├── Gaming PC 4
├── Gaming PC 5
├── Gaming PC 6
├── Gaming PC 7
├── Gaming PC 8
└── Billing Computer
```

### Justification

- The **router** must be connected first because it establishes the internet connection with the ISP, assigns IP addresses using DHCP, performs NAT, and provides firewall security.
- The **switch** is connected after the router because it efficiently connects multiple wired devices within the Local Area Network (LAN).
- Using a **Gigabit switch** ensures high-speed, low-latency communication between gaming PCs, providing a smooth multiplayer gaming experience and uninterrupted IPL streaming.

---

DAY 3 :- Configuring Basic Network Hardware
---

# Task 1 – Router Login Page

## Router Login Screenshot

![Router Login Page](/router-login-page.png)

### Router Details

| Item | Value |
|------|------|
| Default IP Address | YOUR ROUTER IP |
| Login URL | http://YOUR_ROUTER_IP |
| Router Brand | YOUR ROUTER BRAND |

### Description

The router login page was accessed using the router's default gateway address through a web browser. The login page requires an administrator username and password to access the router configuration panel.

---

# Task 2 – IP Configuration

## Device Network Information

| Parameter | Value |
|-----------|-------|
| IPv4 Address | YOUR IP ADDRESS |
| Subnet Mask | YOUR SUBNET MASK |
| Default Gateway | YOUR DEFAULT GATEWAY |

### Description

The IP configuration was obtained while the device was connected to the home Wi-Fi network using the operating system's network settings (or the `ipconfig` command in Windows).

---

# Task 3 – Static IP Configuration

## Static IP Settings Used

| Setting | Value |
|---------|------|
| IP Address | YOUR STATIC IP |
| Subnet Mask | YOUR SUBNET MASK |
| Default Gateway | YOUR DEFAULT GATEWAY |
| Preferred DNS | YOUR DNS |

### Internet Test Result

✅ Internet Connection Working

### Description

The device's network settings were temporarily changed from DHCP (automatic) to a static IP address within the same subnet as the router. After testing internet connectivity, the network settings were restored to automatic (DHCP) to avoid future IP conflicts.

---

# Task 4 – DHCP Range

## DHCP Configuration Screenshot

![DHCP Settings](/dhcp-settings.png)

### Current DHCP Range

| Setting | Value |
|---------|------|
| DHCP Start Address | YOUR START ADDRESS |
| DHCP End Address | YOUR END ADDRESS |

### What Happens if Two Devices Have the Same IP Address?

If two devices on the same network are assigned the same IP address, an **IP address conflict** occurs. As a result, one or both devices may lose internet connectivity, experience communication failures, or frequently disconnect from the network because the router cannot uniquely identify each device.



---

DAY 4 :- Network Cable Types And Tools 
---

# Task 1 – Ethernet Cable vs Fiber Optic Cable

## Differences Between Ethernet and Fiber Optic Cables

| Feature | Ethernet Cable | Fiber Optic Cable |
|----------|----------------|-------------------|
| Transmission Medium | Copper wires transmit electrical signals | Glass or plastic fibers transmit light signals |
| Speed & Distance | Up to 10 Gbps, maximum 100 meters | 100+ Gbps over several kilometers |
| Cost | Low cost and easy to install | Higher cost and requires specialized equipment |

---

## Real-World Examples

### Ethernet Cable
**Example:** Home Wi-Fi router connected to desktop computers, printers, gaming consoles, and smart TVs.

### Fiber Optic Cable
**Example:** Internet Service Provider (ISP) backbone, data centers, and college campus backbone networks.

---

# Task 2 – T568B Straight-Through Ethernet Cable Wiring

## T568B Wiring Diagram

![T568B Wiring Diagram](/t568b-wiring-diagram.png)

---

## Pin Configuration (T568B Standard)

| Pin | Wire Color |
|-----|------------|
| 1 | White / Orange |
| 2 | Orange |
| 3 | White / Green |
| 4 | Blue |
| 5 | White / Blue |
| 6 | Green |
| 7 | White / Brown |
| 8 | Brown |

---

## Wiring Sequence

```
RJ45 Connector (Front View)

 -------------------------
|1|2|3|4|5|6|7|8|
-------------------------

1  White/Orange
2  Orange
3  White/Green
4  Blue
5  White/Blue
6  Green
7  White/Brown
8  Brown
```

A straight-through Ethernet cable uses the **same T568B wiring standard on both ends**, making it suitable for connecting devices such as computers to switches or routers.

---

# Task 3 – Steps to Attach an RJ45 Connector to a CAT6 Cable

## Step-by-Step Procedure

### Step 1
Cut the CAT6 cable cleanly using a cable cutter.

### Step 2
Remove approximately 2–3 cm of the outer insulation using a cable stripper without damaging the internal wires.

### Step 3
Untwist the four twisted wire pairs and straighten all eight wires carefully.

### Step 4
Arrange the wires according to the **T568B wiring standard**:

1. White/Orange
2. Orange
3. White/Green
4. Blue
5. White/Blue
6. Green
7. White/Brown
8. Brown

### Step 5
Trim the wires evenly so they are all the same length.

### Step 6
Insert the wires into the RJ45 connector, ensuring each wire reaches the front end of the connector and remains in the correct order.

### Step 7
Place the RJ45 connector into the RJ45 crimping tool.

### Step 8
Press the crimping tool firmly until the connector locks onto the cable and the metal contacts pierce the wire insulation.

### Step 9
Repeat the same procedure on the other end of the cable if creating a straight-through cable.

### Step 10
Use a cable tester to verify that all eight wires are correctly connected and functioning.

---

# Task 4 – Gaming Café Network Setup

## Scenario

A gaming café with **10 desktop PCs** is being set up for multiplayer LAN gaming and high-speed internet access.

### Selected Cable

**CAT6 Ethernet Cable**

### Selected Tool

**RJ45 Crimping Tool**

### Justification

A CAT6 Ethernet cable is the most suitable choice because the distance between the gaming PCs and the network switch is less than 100 meters. It provides speeds up to **10 Gbps**, offers low latency for online gaming, is cost-effective, and is easy to install. An RJ45 crimping tool is required to attach RJ45 connectors to the Ethernet cables, making installation simple and affordable compared to fiber optic equipment.

---

DAY 5 :- Network Testing
---

# Task 1 – Ping Test Between Two Devices

## Network Setup

Both devices were connected to the same Wi-Fi network.

| Device | IP Address |
|---------|------------|
| Laptop | YOUR_LAPTOP_IP |
| Friend's Phone | FRIEND_PHONE_IP |

### Command Used

```cmd
ping IP
```

### Command Output



### Observation

The ping command was used to verify communication between the laptop and the smartphone connected to the same Wi-Fi network. The devices successfully exchanged ICMP Echo Request and Echo Reply packets, confirming network connectivity.

---

# Task 2 – Traceroute to YouTube

### Command Used

```cmd
tracert www.youtube.com
```

### Number of Hops

**Total Hops:** 30

### Observation

Traceroute displayed every router (hop) between the local network and YouTube's server. Each hop represents an intermediate networking device that forwards packets toward the destination.

---

# Task 3 – Ping After Disconnecting the Phone

The smartphone was disconnected from the Wi-Fi network.

### Command

```cmd
ping IP
```


### Observation

After disconnecting the phone from the Wi-Fi network, the ping request failed because the destination device was no longer reachable.

Typical error messages include:

- Request timed out.
- Destination host unreachable.
- General failure.

---

# Task 4 – Devices Connected to Home Wi-Fi

### Command Used

```cmd
arp -a
```

### Connected Devices

| IP Address | MAC Address | Device Name | Owner |
|------------|-------------|-------------|-------|
| YOUR_ROUTER_IP | XX-XX-XX-XX-XX-XX | Wi-Fi Router | Home Router |
| DEVICE_IP | XX-XX-XX-XX-XX-XX | Laptop | Me |
| DEVICE_IP | XX-XX-XX-XX-XX-XX | Smartphone | Friend |
| DEVICE_IP | XX-XX-XX-XX-XX-XX | Smart TV | Family |
| DEVICE_IP | XX-XX-XX-XX-XX-XX | Printer | Home Printer |

---

# Task 5 – Network Testing Report

## Objective

The objective of this experiment was to understand basic network connectivity by performing Ping, Traceroute, and ARP commands on a home Wi-Fi network.

## Procedure

1. Connected a laptop and a smartphone to the same Wi-Fi network.
2. Used the **ipconfig** command to determine the laptop's IP address.
3. Identified the smartphone's IP address from the router or device settings.
4. Executed the **ping** command from the laptop to the smartphone.
5. Verified successful communication through ICMP replies.
6. Executed the **tracert www.youtube.com** command to observe the network path.
7. Counted the total number of network hops.
8. Disconnected the smartphone from Wi-Fi.
9. Executed the **ping** command again and observed the error message.
10. Executed **arp -a** to display devices connected to the local network.
11. Recorded the IP addresses and identified each connected device.

## Results

- The ping command successfully verified communication while both devices were connected.
- Traceroute displayed multiple intermediate routers between the local network and YouTube.
- After disconnecting the smartphone, the ping command failed because the destination host became unreachable.
- The ARP table displayed the IP and MAC addresses of devices connected to the local network.

## Conclusion

The practical demonstrated how to test communication between devices using the Ping command, trace packet routes using Traceroute, and identify connected devices using the ARP table. These networking tools are essential for troubleshooting and diagnosing network connectivity issues.

---




