# 1. NETWORKING

## 1.1 LAN

### 1.1.1 LAN TOPOLOGIES

### 1.1.2 SUBNETTING

### 1.1.3 ARP PROTOCOL

### 1.1.4 DHCP PROTOCOL

> DHCP is like a ping-pong ball tossed between a device and a network. First of all, it stands for Dynamic Host Configuration Protocol. 

> For example, when a device connects to a network:

1. If a device has not manually decided IP, then the device sends out a request to the network asking "Can I use this IP?" (DHCP Discover)

1. Depending on the uniqueness of IP, the network will suggest its own IP asking, "Would you like to use this IP?" (DHCP Offer)

1. If device wants to use the offered IP, then it will request the network asking, "Can I use it?" (DHCP Request)

1. DHCP Server responds with "yes, you can", send confirmation, then the device can use that IP. (DHCP ACK)
    
## 1.2 OSI MODEL

### 1.2.1 Application (Layer 7)

> GUI, DNS, Filezilla, Browser

### 1.2.2 Presentation (6)

> Regardless of application, data should be translated so that both sender and receiver understand the data. HTTPS is an example

### 1.2.3 Session (5)

> if connection is active, then so is session

> synchronises the two computers to ensure that they are on the same page before data is sent and received

> data cannot travel over different sessions, but in fact, only across each session instead

### 1.2.4 Transport (4)
### 1.2.5 Network (3)
### 1.2.6 Datalink (2)
### 1.2.7 Physical (1)

