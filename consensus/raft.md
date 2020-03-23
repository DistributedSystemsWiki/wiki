---
title: Raft
parent: Consensus
---

# Raft

## Overview

Raft offers a generic way to distribute a state machine across a cluster of computing systems, ensuring that each node in the cluster agrees upon the same series of state transitions.
Raft implements consensus by a leader approach, where only one can be it and the others are all followers. 

The consensus problem is divided in two main parts:

* Leader election
* State Replication 
