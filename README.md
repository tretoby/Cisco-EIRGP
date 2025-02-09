# Network Topology & EIGRP Configuration Project

## 📌 Project Overview

This project demonstrates the setup and configuration of a **small-scale network topology** using **routers, switches, and PCs**, including the implementation of **EIGRP (Enhanced Interior Gateway Routing Protocol)** for efficient inter-network communication. 

The objective of this project is to **design, configure, and verify** a functional network where two separate networks can communicate using **dynamic routing protocols**. This showcases fundamental **networking skills** relevant to **IT support, network administration, and cybersecurity roles**.

---

## 🔹 Skills Demonstrated

✅ **Network Design & Topology** – Selecting and interconnecting network devices (PCs, switches, routers).  
✅ **IP Addressing & Subnetting** – Assigning static IP addresses, setting default gateways.  
✅ **Router & Switch Configuration** – Naming routers, configuring interfaces, enabling connectivity.  
✅ **Dynamic Routing (EIGRP)** – Implementing and verifying **EIGRP** for efficient routing between networks.  
✅ **Troubleshooting & Verification** – Using `show ip route`, `ping`, and interface status checks to confirm connectivity.  

---

## 🔹 Technologies Used

- **Cisco Packet Tracer** (or equivalent network simulation tool)
- **EIGRP (Enhanced Interior Gateway Routing Protocol)**
- **IPv4 Addressing & Subnetting**
- **Copper Straight-Through Cables** (for proper device connections)
- **Basic Cisco Router & Switch CLI Commands**

---

## 🛠️ Network Topology

<img width="1287" alt="Network Topology" src="https://github.com/user-attachments/assets/2e9d4746-83dd-4d2e-9ac8-47097a43d713" />

---

## 🚀 Project Steps

### Step 1: Selecting PCs
First, I will select two PCs.

![PC Selection](https://github.com/user-attachments/assets/c58d85b2-6ef4-49ae-8732-4a9128c23f2d)

### Step 2: Selecting Switches
Next, I will add two network switches.

![Switch Selection](https://github.com/user-attachments/assets/a5164cfd-42f7-4dab-8ba1-b50dfd6c70ac)

### Step 3: Selecting Routers
Then, I will add two routers.

![Router Selection](https://github.com/user-attachments/assets/83cea8ef-1d89-433c-aa20-d75546e61516)

### Step 4: Configuring IP Addresses and Naming Routers
I will now assign IP addresses to the PCs, set the default gateways on the routers, and rename the routers to **Milwaukee** and **Chicago**.

![IP Configuration](https://github.com/user-attachments/assets/76402dc4-0df9-471b-b121-0f73e5817fc6)

### Step 5: Connecting Devices
I will now connect the PCs, switches, and routers using **copper straight-through cables**.

![Connecting Devices](https://github.com/user-attachments/assets/1fe5b3a2-377e-4048-be63-eb200618c779)

### Step 6: Configuring the PCs
Each PC will be assigned an IP address and a default gateway.

![PC Configuration 1](https://github.com/user-attachments/assets/3b087d41-c5b9-4a39-8225-8c04047b7d5f)
![PC Configuration 2](https://github.com/user-attachments/assets/806d403f-cb24-44c3-aba2-8f9a75e3eaf6)

### Step 7: Configuring the Milwaukee Router
The **Milwaukee router** will be configured by setting its hostname and network interfaces.

![Milwaukee Router Configuration](https://github.com/user-attachments/assets/02946670-caf4-4a85-9b7c-8ab5f41dc6e2)

### Step 8: Configuring the Chicago Router
Similarly, I will configure the **Chicago router** with its hostname and interfaces.

![Chicago Router Configuration](https://github.com/user-attachments/assets/b7b3c711-6e6b-4921-bce5-4835691a4c94)

### Step 9: Verifying Connectivity
At this point, all devices should be properly connected, and the network status should indicate **green**, meaning everything is operational.

![Network Status](https://github.com/user-attachments/assets/d3db14b1-e3ae-4653-ba68-3cf2272802b3)

### Step 10: Configuring EIGRP for Router Communication
To enable communication between the PCs across different network segments, I will configure **Enhanced Interior Gateway Routing Protocol (EIGRP)** on both routers.

#### Step 10.1: Checking Initial Routing Table
First, I will check the routing table on the **Milwaukee router** using the `show ip route` command. At this point, only two routes should be present.

![Initial Routing Table](https://github.com/user-attachments/assets/f38eb07d-2d51-4fde-a73c-7c4027a2ed80)

#### Step 10.2: Configuring EIGRP on the Milwaukee Router
Now, I will enable **EIGRP** and specify the network that should be advertised to the **Chicago router**.

![EIGRP Configuration - Milwaukee](https://github.com/user-attachments/assets/b6cd843c-6d79-4109-89c3-3dcd6104846f)

#### Step 10.3: Configuring EIGRP on the Chicago Router
I will now repeat the **EIGRP** configuration on the **Chicago router**.

![EIGRP Configuration - Chicago](https://github.com/user-attachments/assets/a2fab37c-20df-48ea-85ed-a3549a3ac243)

#### Step 10.4: Verifying the Updated Routing Table
After EIGRP is successfully configured, the routing table should now display the added routes.

![Updated Routing Table](https://github.com/user-attachments/assets/7bb20f15-7644-45c5-957f-a6949e3e40e0)

### Step 11: Testing Connectivity
Finally, I will use the `ping` command to verify connectivity between **PC1** and **PC2**.

![Ping Test](https://github.com/user-attachments/assets/19663467-94f4-40dc-bd92-9866478b3e59)

---

## 🎯 Key Takeaways

- **Understanding of Network Devices** – PCs, switches, routers, and cabling.
- **IP Addressing and Routing** – Static IP configuration, gateway settings, and dynamic routing with **EIGRP**.
- **Cisco CLI Experience** – Hands-on experience using **router and switch commands**.
- **Network Troubleshooting** – Using `ping` and `show ip route` for verification.

This project serves as a **real-world networking scenario**, demonstrating the ability to configure, secure, and troubleshoot **enterprise network environments**. It is an excellent showcase of **fundamental networking skills** required for **IT Support, Network Administration, and Cybersecurity roles**.

---

🔹 **Created by:** *Tre Toby*  
