# 🚆 Railway Zone Management System  
### Computer Networks Case Study

![Python](https://img.shields.io/badge/Python-Socket%20Programming-blue)
![Java](https://img.shields.io/badge/Java-Network%20Programming-orange)
![Networking](https://img.shields.io/badge/Domain-Computer%20Networks-green)
![Status](https://img.shields.io/badge/Project-Academic%20Case%20Study-lightgrey)

---

## 📌 Project Overview

This project is a **Computer Networks Case Study** titled **"Railway Zone Management"**.

Railway zones play a crucial role in maintaining and managing railway operations. Each railway zone headquarters must manage:

- Passenger data  
- Reservation systems  
- Catering services  
- Hospital services  
- Accounts and finance  
- Communication between stations  

This project demonstrates how networking concepts, routing protocols, socket programming, and cloud virtualization can be used to build an effective communication architecture within a railway zone.

---

## 🎯 Objectives

- Design a network architecture for a Railway Zone
- Implement client-server communication using **Socket Programming**
- Demonstrate **File Handling using CSV**
- Implement **Go-Back-N / Selective Repeat ARQ** (Java)
- Configure **VLAN, RIP, and OSPF routing**
- Explain performance metrics such as Bandwidth, Throughput, and Latency
- Understand Cloud Virtualization concepts

---

# 🌐 Network Architecture

## 🏢 Departments & Network Types

| Department | Network Type |
|------------|-------------|
| Tourism & Catering | Wide Area Network (WAN) |
| Railway Reservation | WAN |
| Railway Hospital | Local Area Network (LAN) |
| Accounts Department | Virtual Private Network (VPN) |

---

# 📊 Network Performance Parameters

### 1️⃣ Bandwidth
- Maximum data transmission capacity (bps, Mbps, Gbps)
- Typical range: **10 – 1000 Mbps**

### 2️⃣ Throughput

Throughput = (Frames × Bits per frame) / Unit time

### 3️⃣ Latency

Latency = Propagation + Transmission + Queuing + Processing Delay

Typical range: **1ms – 20ms**

### 4️⃣ Bandwidth-Delay Product

Bandwidth × Delay



### 5️⃣ Jitter
- Variation in packet delay  
- Ideal: **< 30ms**

---

# 🖥️ System Configuration

## 🔹 Client Configuration
- Intel Core 4005U Processor
- 8GB RAM
- 1TB Storage

## 🔹 Server Configuration
- Intel Itanium 2 Processor
- 23.98GB RAM
- 4.5TB Storage (EMC Box)

---

# 🖧 Network Components

## 🔹 Servers Used
- Database Server
- Proxy Server
- Mail Server
- Application Server
- Client Server

## 🔹 Cables Used
- Coaxial Fiber
- Twisted Fiber
- Optical Fiber

## 🔹 Topologies
- Star Topology (Reservation, Accounts, Catering)
- Bus Topology (Medical Department)

---

# 💻 Socket Programming – Catering Department

Implemented a **Client-Server Architecture** in Python to manage food ordering for railway passengers.

## 📁 CSV Files Used

### 1️⃣ CATERING-DEPARTMENT.csv
Fields:
name, item_name, quantity, station, train_name, time, timestamp, status

### 2️⃣ items_list.csv
Fields:

s.no, item_name, quantity, price



---

## 🛠 Functionalities Implemented

| Key | Operation |
|-----|----------|
| W | View Menu |
| I | Order Food |
| M | Cancel Order |
| V | View Order Status |

---

## 🖥️ Server Side (Python)
- Multi-threaded server using `socket` and `threading`
- Handles multiple clients
- Reads/Writes CSV using `pandas`
- Performs:
  - Insert order
  - Update status
  - Retrieve menu
  - Retrieve order data

---

## 💻 Client Side (Python)
- Connects to server using socket
- Sends user commands
- Displays updated CSV data
- Supports multiple clients

---

# 📦 Java Implementation – Go-Back-N Protocol

Implemented ARQ protocol simulation using Java:

### Files:
- `Server.java`
- `Client.java`

### Functionality:
- Sends frames
- Simulates frame loss
- Requests retransmission
- Demonstrates Go-Back-N behavior

---

# 🌐 Routing Protocols Implemented

## 🔹 VLAN
- Logical segmentation of network
- Improves performance & security

## 🔹 Inter-VLAN Routing
- Enables communication between VLANs

## 🔹 RIP (Routing Information Protocol)
- Distance Vector Protocol
- Hop count based routing

## 🔹 OSPF (Open Shortest Path First)
- Link-State Protocol
- Faster convergence than RIP

---

# ☁️ Cloud Virtualization

### Key Concepts:
- Infrastructure as a Service (IaaS)
- Software as a Service (SaaS)
- Virtual Servers
- Virtual Storage
- Resource Scaling

### Benefits:
- Cost efficiency
- Scalability
- Resource optimization
- Easy migration
- Hardware abstraction

---

# 📁 Project Structure

- ├── Catering_server.py
- ├── Catering_client1.py
- ├── Catering_client2.py
- ├── Server.java
- ├── Client.java
- ├── CATERING-DEPARTMENT.csv
- ├── items_list.csv
- └── README.md


# 🚀 How to Run

## 🔹 Run Python Server

`python Catering_server.py`

🔹 Run Python Client
python Catering_client1.py
🔹 Run Java ARQ Simulation
javac Server.java
javac Client.java
java Server
java Client



## Concepts Covered

- Computer Network Architecture
- WAN, LAN, VPN
- VLAN Configuration
- RIP & OSPF Routing
- Socket Programming
- File Handling with CSV
- Multithreading
- Go-Back-N ARQ
- Cloud Virtualization



## Author

- T. Krishna Chaitanya
- CB.EN.U4CSE19153
- Tourism & Catering Department – Railway Zone Case Study
