# CMU-15640-25Fall
# Distributed Systems
[Prof. Miller](https://heather.miller.am/) | Associate Professor of Computer Science at CMU

[Prof. Zheng](https://wzheng.github.io/) | Associate Professor of Computer Science at CMU

[Course Official Website](https://www.composablesystems.org/15-440/fa2025/) | [Course GitHub Site](https://github.com/15-440) | [CMU SCS Description](https://www.csd.cs.cmu.edu/course/15640/f25)

## Proj0: KV Messaging Systems & Go Testing
Projet0 focuses on giving us a introduction to Go programming and testsing, which will be further used in all later projects
- **Key Words:** Go subroutine, mulit-thread programming, socket programming, Go-style synchronization control, key-value database server, Go testing, etc.

### Part A
Part A of Proj0 is to implement the backend, a key-value database server, of a simple online messaging system, where every clients can read or modify every other clients' messages. 

My solution has the following features included:
1. Server Characteristics: Put(K string, V []byte), Get(K string) []([]byte), Delete(K string), Update(K string, V1 []byte, V2 []byte)
2. Concurrent requirements: There are **no race conditions** when accessing the database server, which guarantees the safety and liveness of the backend.
3. Synchronization control: All synchronizations are done by using **goroutines, channels, and Go’s channel-based select statement with not locks and mutexes**.

### Part B
Part B of Proj0 is to write Go-style test cases for testsing a Squarer, which transforms a channel of integers to a channel that transmits the squares of those integers.

There is one correct implementation provided which satifies all requirments in the API doc and **we should write our own Go test cases to test each properties descriped against the correct one.**

## Proj1: Distributed Bitcoin Miner
### Part A

### Part B

## Proj2: The Raft Consensus Algorithm
[Paper](https://raft.github.io/raft.pdf) | [Site](https://raft.github.io/) | [Illustration](https://thesecretlivesofdata.com/raft/)
## Proj3: CMUD


# Disclaimer
This repository only contains descriptions of the projects I worked on during this class. As per the [Academic Integrity (AI) Policy of CMU](https://www.cmu.edu/policies/student-and-student-life/academic-integrity.html), all solutions and code are stored separately in private repositories.

If you are a hiring manager evaluating my skills, or if you are simply interested in contributing to its further development, please contact me via email.