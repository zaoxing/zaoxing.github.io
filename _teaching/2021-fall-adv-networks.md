---
title: "Advanced Computer Networking"
collection: teaching
type: "PhD Seminar"
permalink: /teaching/2021-fall-adv-networks
venue: "Boston University, ECE"
date: 2021-09-01
location: "Boston, MA"
---

The Internet today carries a great volume and variety of data to enable new waves of innovation. This course is to explore the principles and design decisions which underly the Internet. It provides a comprehensive overview of advanced topics in network protocols and networked systems. Lectures will cover both classic papers on Internet protocols and recent research advances. The course aims to examine a wide range of topics, e.g., switching and routing, congestion control, network architectures, data center networks, network virtualization, software-defined networking, and programmable networks, with an emphasis on core networking concepts and principles. The concepts will be reinforced with paper
discussions, programming assignments, and a final project.

Instructors
------
* Instructor: Prof. Alan (Zaoxing) Liu
    * Office Hours: Thu 3-4 or by appointment

Prerequisites
------
Experiences with software systems and computer networking, including one or more of EC 508, EC528, EC 541, etc., or permission of the instructor. The assignments and projects assume students have familiarity with programming (e.g., Python and C/C++).

Textbook
------
There are no mandatory textbooks for this course, but every class will have corresponding readings from research papers. A reading list with links to the papers will be provided.

Course Overview
------
1. **Lectures:** In each topic, the instructor will give one or two introductory lectures, followed by paper presentations by class participants.

2. **Paper Reviews:** Each student reviews 1 paper/class from top conferences or journals. Submit reviews before the class in four sections, including summary, paper strengths paper weaknesses, and  detailed comments.

3. **Paper Presentations:** Each student will select papers from the paper reading list (the list will be provided, selections are first-come first-serve) and present that paper during a lecture. The presentation will be followed by a technical discussion.

4. **Programming Assignments:** There will be (tentatively) two programming assignments during the class. These assignments assume basic networking knowledge and some familiarity with network programming.

5. **Project:** This class has a final project:  
    a.	Topic: Reproduce a paper discussed in class, or novel research with a system-building component.  
    b.	Can work alone, or in groups of two students. Must involve writing some code.  
    c.	Can overlap with other research projects, with permission.


Academic Conduct Statement
------
 Academic Conduct Statement including expectations for academic honesty, reference to consequences for cheating or plagiarism, course-specific guidelines for, e.g., extent of allowable collaboration on assignments, and URL for [Academic Conduct Code](https://www.bu.edu/academics/policies/academic-conduct-code/).

Grading
------
- Class participation: 20% 
- Paper reviews: 20% 
- Programming assignments: 20% 
- Project report and presentation: 40%

Late Policy: Programming assignments receive 25% off grades for each 24 hours late, rounded up




Course Schedule
------

| Topics  | Readings |
| :------: | :------: |
| Course Overview |  “How to Read a Paper?”, S.Keshav; “You and Your Research”, J.F. Kaiser |
| End-host System |  “A Protocol for Packet Network Intercommunication”, Vint Cerf and Bobert Kahn;     “End-to-End Arguments in System Design”,  J. H. Saltzer, D. P. Reed, D. D. Clark |
| Control Plane |  “The Design Philosophy of The DARPA Internet Protocols”, David D. Clark; “End-to-End Routing Behavior in the Internet”, Vern Paxson |
| Data Plane |  “The Click Modular Router”, Eddie Kohler, Robert Morris et al., TOCS’00; “P4: Programming Protocol-Independent Packet Processors”, Pat Bosshart et al., SIGCOMM CCR’14; -Additional Reading: “Forwarding Metamorphosis: Fast Programmable Match-Action Processing in Hardware for SDN”, Pat Bosshart et al., SIGCOMM’13 |
| Overlay Networks |  “Chord: A Scalable Peer-to-Peer Lookup Service for Internet Applications”, Ion Stoica et al., SIGCOMM’01; “A Scalable Content-Addressable Network”, Sylvia Ratnasamy et al., SIGCOMM’01 |
| Looking Forward: The Big Picture |  “A New Golden Age for Computer Architecture”, John Hnnessy and David Patterson; “Attack of the Killer Microseconds”, Luiz Barroso et al. |
| Data Center Networking: Architectures | “VL2: A Scalable and Flexible Data Center Network”, Albert Greenberg et al., SIGCOMM’09; “Jupiter Rising: A Decade of Clos Topologies and Centralized Control in Google’s Datacenter Network”, Arjun Singh et al., SIGCOMM’15 |
| Data Center Optical Networks | “Helios: A Hybrid Electrical/Optical Switch Architecture for Modular Data Center”, Nathan Farrington et al., SIGCOMM’10; “ProjecToR: Agile Reconfigurable Data Center Interconnect”, Monia Ghobadi et al., SIGCOMM’16 |
| Network Measurement/Sketch | “One Sketch to Rule Them All: Rethinking Network Flow Monitoring with UnivMon”, Zaoxing Liu at al., SIGCOMM’16; “NitroSketch: Robust and General Sketch-based Monitoring in Software Switches”, Zaoxing Liu at al., SIGCOMM’19 |
| Congestion Control | “Data Center TCP (DCTCP)”, Mohammad Alizadeh et al., SIGCOMM’10; “pFabric: Minimal Near-Optimal Datacenter Transport”, Mohammad Alizadeh et al., SIGCOMM’13; -Additional Reading: “HPCC: High Precision Congestion Control”, Yuliang Li et al., SIGCOMM’19 |
| Resource Disaggregation |  “LegoOS: A Disseminated, Distributed OS for Hardware Resource Disaggregation”, Yizhou Shan et al., OSDI’18 |
| Software-defined Networking | “Ethane: Taking Control of the Enterprise”, Martin Casado et al., SIGCOMM’07; “Onix: A Distributed Control Platform for Large-scale Production Networks”, Teemu Koponen et al., OSDI’07 |
| Wide Area Networks | “B4: Experience with a Globally-Deployed Software Defined WAN”, Sushant Jain et al., SIGCOMM’13; “Achieving High Utilization with Software-Driven WAN”, Chi-Yao Hong et al., SIGCOMM’13 |
| Programmable Networks and Applications | -Caching: “NetCache: Balancing Key-Value Stores with Fast In-Network Caching”, Xin Jin et al., SOSP’17; “DistCache: Provable Load Balancing for Large-Scale Storage Systems with Distributed Caching”, Zaoxing Liu et al., FAST’19; -Consensus: “Just Say NO to Paxos Overhead: Replacing Consensus with Network Ordering”, Jialin Li et al., OSDI’16; “Eris: Coordination-Free Consistent Transactions Using In-Network Concurrency Control”, Jialin Li et al., SOSP’17; -Telemetry: “PINT: Probabilistic In-band Network Telemetry”,  Ran Ben Basat et al., SIGCOMM’20; “Sonata: Query-Driven Streaming Network Telemetry”, Arpit Gupta et al., SIGCOMM’18; -Security: “Jaqen: A High-Performance Switch-Native Approach for Detecting and Mitigating Volumetric DDoS Attacks with Programmable Switches”, Zaoxing Liu et al., USENIX Security’21; “Ripple: A Programmable, Decentralized Link-Flooding Defense Against Adaptive Adversaries”,  Jiarong Xing et al., USENIX Security’21 |
| ML and Networks | - ML for Networked Systems: “Neural Adaptive Video Streaming with Pensieve”, Hongzi Mao et al., SIGCOMM’17; “Network Planning with Deep Reinforcement Learning”, Hang Zhu et al., SIGCOMM’21; “A Deep Reinforcement Learning Perspective on Internet Congestion Control”, Nathan Jay et al., ICML’19; - Networked Systems for ML: “A Generic Communication Scheduuler for Distributed DNN Training Acceleration”, Yanghua Peng et al., SOSP’19; “PipeDream: Generalized Pipeline Parallelism for DNN Training”, Deepak Narayanan et al., SOSP’19; “A Unified Architecture for Accelerating Distributed DNN Training in Heterogeneous GPU/CPU Clusters”, Yimin Jiang et al., OSDI’20 |
| Middleboxes | - NFV Framworks “E2: A Framework for NFV Applications”, Shoumik Palkar et al., SOSP’15; “NetBricks: Taking the V out of NFV”, Aurojit Panda et al., OSDI’16; - Load Balancer “Ananta: Cloud Scale Load Balancing”, Parveen Patel et al., SIGCOMM’13; “SilkRoad: Making Stateful Layer-4 Load Balancing Fast and Cheap Using Switching ASICs”, Rui Miao et al., SIGCOMM’17 |