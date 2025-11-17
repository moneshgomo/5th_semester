# Distributed Computing Syllabus

---

## UNIT I (8 Hrs)
**INTRODUCTION**
- [ ] Definition – Relation to Computer System Components  
- [ ] Motivation  
- [ ] Message-Passing Systems versus Shared Memory Systems  
- [ ] Primitives for Distributed Communication  
- [ ] Synchronous vs Asynchronous Executions  
- [ ] Design Issues and Challenges  
- [ ] A Model of Distributed Computations  
- [ ] A Distributed Program  
- [ ] A Model of Distributed Executions  
- [ ] Models of Communication Networks  
- [ ] Global State of a Distributed System  

---

## UNIT II (10 Hrs)
**LOGICAL TIME AND GLOBAL STATE**
- [ ] Logical Time: Physical Clock Synchronization – NTP  
- [ ] Framework for a System of Logical Clocks  
- [ ] Scalar Time  
- [ ] Vector Time  
- [ ] Message Ordering and Group Communication  
- [ ] Message Ordering Paradigms  
- [ ] Asynchronous Execution with Synchronous Communication  
- [ ] Synchronous Program Order on Asynchronous System  
- [ ] Group Communication  
- [ ] Causal Order – Total Order  
- [ ] Global State and Snapshot Recording Algorithms  
- [ ] Introduction  
- [ ] System Model and Definitions  
- [ ] Snapshot Algorithms for FIFO Channels  

---

## UNIT III (10 Hrs)
**DISTRIBUTED MUTEX AND DEADLOCK**
- [ ] Distributed Mutual Exclusion Algorithms: Introduction – Preliminaries  
- [ ] Lamport’s Algorithm  
- [ ] Ricart-Agrawala’s Algorithm  
- [ ] Token-Based Algorithms  
- [ ] Suzuki-Kasami’s Broadcast Algorithm  
- [ ] Deadlock Detection in Distributed Systems: Introduction – System Model – Preliminaries  
- [ ] Models of Deadlocks  
- [ ] Chandy-Misra-Haas Algorithm for the AND model and OR model  

---

## UNIT IV (10 Hrs)
**CONSENSUS AND RECOVERY**
- [ ] Consensus and Agreement Algorithms: Problem Definition – Overview of Results  
- [ ] Agreement in a Failure-Free System (Synchronous and Asynchronous)  
- [ ] Agreement in Synchronous Systems with Failures  
- [X] Checkpointing and Rollback Recovery – Introduction – Background and Definitions  
- [X] Issues in Failure Recovery  
- [ ] Checkpoint-based Recovery  
- [ ] Coordinated Checkpointing Algorithm  
- [ ] Asynchronous Checkpointing Algorithm and Recovery  

---

## UNIT V (7 Hrs)
**CLOUD COMPUTING**
- [ ] Definition of Cloud Computing  
- [ ] Characteristics of Cloud  
- [ ] Cloud Deployment Models  
- [ ] Cloud Service Models  
- [ ] Driving Factors and Challenges of Cloud  
- [ ] Virtualization – Load Balancing – Scalability and Elasticity – Replication – Monitoring  
- [ ] Cloud Services and Platforms  
- [ ] Compute Services  
- [ ] Storage Services  
- [ ] Application Services  

---

# Important Questions (Based on Previous Pondicherry University Exams)

1. Explain the difference between **message passing systems** and **shared memory systems**.  
2. What are the **design issues and challenges** in distributed computing?  
3. Discuss the **model of distributed executions** with neat diagrams.  
4. Explain **NTP clock synchronization** and vector clocks with examples.  
5. Write short notes on **message ordering paradigms**.  
6. Differentiate between **causal order** and **total order**.  
7. Explain Lamport’s and Ricart-Agrawala’s algorithms for **mutual exclusion**.  
8. Compare **token-based** and **non-token-based** mutual exclusion algorithms.  
9. Explain Suzuki-Kasami’s broadcast algorithm with a diagram.  
10. How are **deadlocks detected** in distributed systems? Explain Chandy-Misra-Haas algorithm.  
11. What are consensus algorithms? Differentiate between synchronous and asynchronous agreements.  
12. Explain **checkpointing and rollback recovery** with suitable examples.  
13. Compare **coordinated and asynchronous checkpointing algorithms**.  
14. Define cloud computing. Explain its **deployment models** and **service models**.  
15. Write short notes on **scalability, elasticity, and replication** in cloud.  
16. Discuss the role of **virtualization and load balancing** in cloud computing.  

---
