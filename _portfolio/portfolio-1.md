---
title: "Sponge – TCP Protocol Implementation"
excerpt: "Short description of portfolio [item](https://github.com/Altman-S/CS144-Computer-Network) number 1<br/><img src='/images/projects/tcp_overall_design.png'>"
collection: portfolio
---

This is the implementation of a TCP (Transmission Control Protocol) in modern C++ called Sponge from Stanford University, which helps to establish a bi-directional reliable in-order data transfer between two endpoints on the Transfer layer in term of the 4-layer network abstraction. Key highlights includes: three-way/four-way handshake(SYN/FIN), segment reordering(stream reassembler), flow control(sliding window), retransmission control(exponential backoff), state transition(finite state machine), etc.
