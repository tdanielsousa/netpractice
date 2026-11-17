# NetPractice

A 42 network administration project designed to teach the fundamentals of TCP/IP networking, addressing, and routing.

The goal is to configure and fix broken network topologies across 10 increasingly complex levels using a web-based training interface, with correct IP addresses, subnet masks, and routes.

> Note: By calculating IP addresses, applying subnet masks, and directing traffic via default gateways and routers, this project bridges theoretical networking concepts with practical configuration logic.
---

<div align="center">
    <br>
    <a href="https://github.com/tdanielsousa/42_School/blob/main/Subjects/netpratice.pdf" target="_blank">
        <img src="https://img.shields.io/badge/View%20Subject-PDF-red?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white" alt="Subject PDF" height="40">
    </a>
    <p><i>Click on the button above to see the subject's pdf.</i></p>

</div>

---

##  Network Architecture & Concepts

The project is built around the core building blocks of a TCP/IP network, each one applied across the 10 levels.

### Technical Specifications
* **TCP/IP Addressing:** Configuring static IPv4 addresses across network interfaces and validating host accessibility within local subnets.
* **Subnet Masks:** Utilizing variable-length subnet masks and CIDR notation to define network boundaries, broadcast addresses, and usable host ranges.
* **Default Gateways:** Assigning gateway addresses to forward outbound network traffic to destination subnets outside the local broadcast domain.
* **OSI Layers:** Analyzing data flow across the OSI model, focusing on Layer 2 (Data Link - MAC/Switching) and Layer 3 (Network - IP/Routing) operations.

---

##  Devices & Routing Logic

### Switches (Layer 2)
Connect devices within the same subnet to allow direct intra-network communication.

### Routers (Layer 3)
Route IP packets across distinct subnets using configured routing tables and gateway hops.

---

##  Training Modes

The web interface offers two ways to practice:

* **Training:** 10 progressive levels of increasing complexity.
* **Evaluation:** 3 random levels picked from levels 6 to 10.

---

## Installation & Run Steps

### 1. Launch the Interface
Run the startup script from the root of the repository:

    ./run.sh

### 2. Access NetPractice
Open your web browser and navigate to `http://localhost:8080` (or the port specified in your terminal output).

### 3. Solve the Levels
Select Training or Evaluation and fix each topology.

---

## Exporting Configurations

Once a level is successfully solved in the interface:

* Click the **Export** button (get my config) to generate the level's `.json` file.
* Save or move each exported file to the root of your repository.

### Submission Requirements
To successfully submit the project, your Git repository must include:

* All 10 exported configuration files placed directly at the repository root (`level-1` through `level-10`).
* This `README.md` file at the repository root.

---

## References

* **[Video series about subnetting and addressing](https://www.youtube.com/watch?v=5WfiTHiU4x8)**
* **[Subnetting](https://www.geeksforgeeks.org/computer-networks/introduction-to-subnetting/)**
* **[TCP/IP Addressing](https://www.ibm.com/docs/en/aix/7.2.0?topic=protocol-tcpip-addressing)**
* **[OSI Layers](https://www.geeksforgeeks.org/computer-networks/open-systems-interconnection-model-osi/)**

---

## AI Usage Declaration

AI tools were utilized during this project for the following tasks:

* **Subnet Calculation Verification:** Subnet calculations and host ranges for complex levels.
* **Documentation Support:** Structuring and drafting the README file according to 42's NetPractice subject guidelines.
* **Concept Clarification:** Generating targeted explanations for router hop logic and gateway reachability rules.

---
