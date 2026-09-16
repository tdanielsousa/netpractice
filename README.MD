*This project has been created as part of the 42 curriculum by tdaniel-*

# NetPractice

## Description

NetPractice is a 42 network administration project designed to teach the fundamentals of TCP/IP networking, addressing, and routing. 
The core objective is to configure and fix broken network topologies across 10 increasingly complex levels using a web-based training interface. 

By calculating IP addresses, applying subnet masks, and directing traffic via default gateways and routers, this project bridges theoretical networking concepts with practical configuration logic.

---

## Instructions

### Running the Training Interface

1. Launch the Interface: Run the startup script from the root of the repository:
   ./run.sh
2. Access NetPractice: Open your web browser and navigate to http://localhost:8080 (or the port specified in your terminal output).
3. Select either Training (10 progressive levels) or Evaluation(3 randoms levels from 6 to 10).
4. Solve the Levels.

### Exporting Configurations

* Once a level is successfully solved in the interface, click the Export button (get my config) to generate the level's json file.
* Save or move each exported file to the root of your repository.

### Submission Requirements

To successfully submit the project, your Git repository must include:
* All 10 exported configuration files placed directly at the repository root (level-1 through level-10).
* This README.md file at the repository root.

---

## Resources


### Concepts Covered

* **TCP/IP Addressing:** Configuring static IPv4 addresses across network interfaces and validating host accessibility within local subnets.
* **Subnet Masks:** Utilizing variable-length subnet masks and CIDR notation to define network boundaries, broadcast addresses, and usable host ranges.
* **Default Gateways:** Assigning gateway addresses to forward outbound network traffic to destination subnets outside the local broadcast domain.
* **Routers and Switches:** 
  * **Switches (Layer 2):** Connecting devices within the same subnet to allow direct intra-network communication.
  * **Routers (Layer 3):** Routing IP packets across distinct subnets using configured routing tables and gateway hops.
* **OSI Layers:** Analyzing data flow across the OSI model, focusing on Layer 2 (Data Link - MAC/Switching) and Layer 3 (Network - IP/Routing) operations.


### Networking References

* Video series about subnetting and addressing: https://www.youtube.com/watch?v=5WfiTHiU4x8
* Subnetting: https://www.geeksforgeeks.org/computer-networks/introduction-to-subnetting/
* TCP/IP Adressing: https://www.ibm.com/docs/en/aix/7.2.0?topic=protocol-tcpip-addressing
* OSI Layers: https://www.geeksforgeeks.org/computer-networks/open-systems-interconnection-model-osi/

### AI Usage Declaration

AI tools were utilized during this project for the following tasks:
* Subnet Calculation Verification: Subnet calculations and host ranges for complex levels.
* Documentation Support: Structuring and drafting the README file according to 42's NetPractice subject guidelines.
* Concept Clarification: Generating targeted explanations for router hop logic and gateway reachability rules. 

---
