# [Open Shortest Path First TEST] - Network Simulation Lab

A comprehensive network design and simulation built and tested with PnetLab. This lab demonstrates [briefly describe the goal, e.g., multi-area OSPF routing, enterprise network design, or BGP peering].

![Network Topology Diagram](images/topology-diagram.png) <!-- Highly recommended! -->

## 📋 Lab Overview

This lab consists of a network designed to simulate a [real-world scenario, e.g., small corporate network, data center interconnect]. The topology includes:

*   **Routers:** [10  ]
*   **Switches:** [10  ]
*   **End Devices:** [10 PC ]
*   **Key Technologies & Protocols:**
    *   OSPF (Open Shortest Path First)
    
## 🚀 Getting Started with PnetLab

These instructions will get a copy of the lab running on your local PnetLab installation.

### Prerequisites

Before importing this lab, you need to have the following:
*   **PnetLab** installed and running on your system or server.
    *   [Download PnetLab](https://www.pnetlab.com/)
*   Ensure you have the appropriate **QEMU images** for the nodes used in this lab (e.g., `x86_64_crb_linux-adventerprisek9-ms.bin`, `x86_64_crb_linux_l2-adventerprisek9-ms.bin`, `Mikortik 7.19`) already installed in your PnetLab.

### Download Link 

   * `[x86_64_crb_linux-adventerprisek9-ms.bin](https://download.netlabplus.com/images/Cisco/IOL/IOS%20XE%2017/)` 
   * `[x86_64_crb_linux_l2-adventerprisek9-ms.bin](https://download.netlabplus.com/images/Cisco/IOL/IOS%20XE%2017/) ` 
   * `[Mikrotik](https://download.mikrotik.com/routeros/7.19.3/chr-7.19.3.img.zip))` 


### Installation & Import

1.  **Download the Lab File:**
    *   Clone this repository or download the `[[OSPF_TEST.zip](https://github.com/MMDoraghi/OSPF-LAB-CISCO-CCNA/blob/main/OSPF%20Testing.unl)]` file.

2.  **Import into PnetLab:**
    *   Log in to your PnetLab dashboard.
    *   Navigate to **My Labs**.
    *   Click the **Import** button.
    *   Browse and select the `[OSPF_TEST.unl]` file you downloaded.
    *   Click **OK** to begin the import process.

3.  **Wait for Initialization:**
    *   Once imported, click on the lab to open it.
    *   PnetLab will need to extract and prepare the lab. This may take a few moments.

## 🧪 Using the Lab

1.  **Start the Lab:**
    *   Inside the lab workspace, click the **Start** button (play icon) to power on all network devices.

2.  **Access the Devices:**
    *   Wait for all nodes to boot up (their status indicators will turn green).
    *   You can console into any device by double-clicking on it. This will open a new tab with a CLI session.

3.  **Pre-configured Settings:**
    *   **Important:** The lab is pre-configured according to the design. Key configurations (IP addresses, routing protocols) are already applied.
    *   You can begin testing and validating the network immediately.

4.  **Validation & Testing:**
    *   Use `ping` and `traceroute` between end devices to verify connectivity.
    *   Use CLI commands like `show ip route`, `show ip ospf neighbor`  on routers and switches to verify protocol operation.

5- ** Mikrotik Login ** 
   * user 'admin 
   * pass : ' ccna ' 





