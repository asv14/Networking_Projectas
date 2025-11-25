Enterprise Multi-Area OSPF & Multi-AS EIGRP Routing Lab Using Redistribution, Virtual Link


*Topology Overview
- The network consists of interconnected OSPF and EIGRP domains, built to test advanced routing behavior, convergence, and multi-protocol interaction.
-	OSPF Domain (Backbone + Additional Area)
-	Multi-Area OSPF deployed between R1, R2, R3, and R4.
-	Backbone routing ensured via Area 0, serving as the primary transit for all other OSPF areas.
-	Additional OSPF area connected to validate inter-area route propagation and LSA exchange.
-	EIGRP Domains (Multiple Autonomous Systems)
-	EIGRP AS 7 operating between R2 and R7
-	EIGRP AS 9 operating between R5 and R9.
-	Each EIGRP AS tested independently for neighbour adjacency formation, topology tables, and metric calculations.

*Key Technical Implementations
-	Configured Multi-Area OSPF with correct backbone alignment for stable inter-area routing.
-	Implemented multiple EIGRP AS with proper adjacency formation and topology table verification.
-	Ensured inter-domain reachability across OSPF and EIGRP networks.


*Validation & Testing
-	Confirmed end-to-end connectivity across all routers.
-	Implemented Virtual Link on Area 56
-	Achieved loop-free convergence through DUAL and SPF algorithms.
-	Tested link failures and observed OSPF & EIGRP reconvergence behavior.
-	Ensured correct redistribution boundaries.


*Tools Used
-	EVE-NG for network emulation


*Skills Demonstrated
-	Multi-Area OSPF implementation
-	Multi-AS EIGRP deployment
-	Routing design, planning, and troubleshooting


![Red_topo](https://github.com/user-attachments/assets/f54a5ae2-5487-464b-bcf7-29057fc1434c)
