---
layout: default
---
<img class="profile-picture" src="XiaoLiPic.JPG">

## About Me

I am a 4th-year Computer Science Ph.D. candidate at University of California, Riverside (UCR). I am supervised by Prof. [Mohsen Lesani](https://www.cs.ucr.edu/~lesani/). 

## Research Interest

I'm interested in the theory and practice of distributed systems, computer security and programming languages. One of my goals is to fill the gap between abstractions and interfaces of user-friendly sequential objects and complicated replicated objects with the help of type systems and automatic reasoning tools (Z3, CVC4, etc). I'm also interested in the foundation of consensus and distributed system protocols in the heterogenous trust setting. 

Currently, I'm working on designing efficient consensus protocol with open membership.

## News
**Jul/2023**: I am selected to receive the department scholarship to attend Grace Hopper Conference 2023.    
**Jul/2023**:  Our work (On the power of quorum subsumption for heterogeneous quorum systems) is accepted to DISC'23.   
**Mar/2023**:  I am selected to receive Dissertation Year Program Fellowship for 2023/2024.  
**Nov/2022**:  I am selected to receive student travel grant for 2022 ACM CCS.  
**May/2022**:  I am selected to receive GSA travel grant for 2022 IEEE Symposium on Security and Privacy.  
**Apr/2022**:  I am selected to receive student travel grant for 2022 IEEE Symposium on Security and Privacy.  
**Oct/2021**:  I am selected and funded to attend PLMW@SPLASH 2021.  
**Jul/2021**:  Our work Hamraz is accepted to IEEE S&P'22 (accept rate ~15%)!  
**Jul/2020**:  Welcome to my talk in CAV'20 Session 3B about our Hampa paper.     
**Jul/2020**:  Passed my Ph.D. candidacy exam!     
**Apr/2020**:  Our work Hampa is accepted to CAV'20 (44 papers accepted out of 241).    
**Sep/2019**:  Transfered to CS Ph.D. program at University of California, Riverside.    
**Sep/2017**:  Attended University of California, Riverside for CS MS program.    
**Jul/2017**:  Got my B.E. in Information Security from HUST(Huazhong University of Science and Technology) as *OutStanding Graduates*.    

## Ongoing Projects

**Reconﬁgurable Clustered Byzantine Replication**: We design reconfiguration protocols for SMR across multiple clusters. We formally prove the safety and liveness properties of the reconfigurable clustered Byzantine replication and implement this framework for both HotStuff and BFT-Smart. Our experiment results show that clustered BFT SMR provides high throughput and low latency with dynamic membership.

**Open Heterogeneous Quorum Systems**:  We present **reconfiguration protocols** for heterogeneous quorum systems(HQS) in order to enable open membership for permissionless blockchains. We also presents trade-offs for the properties that reconfigurations can preserve, and accordingly, presents reconfiguration protocols and proves their correctness. We further present a **graph characterization of HQS**, and its application for reconfiguration optimization.Our results are available on arXiv now: [Open](https://arxiv.org/abs/2304.02156)


## Previous Projects

**On the power of quorum subsumption for heterogeneous quorum systems**:  We prove an **impossibility result** that shows **quorum intersection, and quorum availability** is not sufficient for Byzantine reliable broadcast(BRB) and consensus in heterogenous quorum systems(HQS), where each process can select different quorums. Moreover, we propose **quorum-subsumption** to help achieve BRB and consensus with detailed protocols and proofs. Quorum-subsumption together with intersection and availability is so far the weakest condition we know for BRB and consensus in the HQS setting.

**Hamraz**:  How to have **confidentiality, integrity, and availability** with as few machine as possible for replicated objects? Better yet, we got the work done automatically. Our open source project are available: [Hamraz: code](https://github.com/XiaoLi0614/Secure_Partition.git)

**Hampa**:  How to keep the **invariant and recency** of replicated objects as user specified with as little coordination as possible? Skip the manual labour and try out our tool with the help of program synthesis and the state-of-art SMT solver. Our tool and open source project are available: [Hampa: tool](https://github.com/XiaoLi0614/HampaAE), [Hampa: code](https://github.com/XiaoLi0614/CVCAutomation)

## Publications
1. [**DISC'23**] **Xiao Li**, Eric Chan, Mhsen Lesani, [On the power of quorum subsumption for heterogeneous quorum systems], *in the 37th International Symposium on Distributed Computing.
2. [**S&P'22**] **Xiao Li**, Farzin Houshmand, Mohsen Lesani, [Hamraz: Resilient Object Partitioning and Replication](https://www.cs.ucr.edu/~lesani/companion/sp22/SP22.pdf), *in the 43rd IEEE Symposium on Security and Privacy, May 2022.
3. [**CAV'20**] **Xiao Li**, Farzin Houshmand, Mohsen Lesani, [Hampa: Solver-aided Recency-Aware Replication](https://www.cs.ucr.edu/~lesani/companion/cav20/CAV20.pdf), *in the 32nd International Conference on Computer-Aided Verification, July 2020.
