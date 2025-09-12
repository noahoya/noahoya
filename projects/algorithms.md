---
layout: project
type: project
image: img/C.png
title: "Java & C Integration with JNI"
date: 2024
published: true
labels:
  - C++
  - Java
  - Pseudocode
  - Algorithm Analysis
summary: "Algorithms learned from ICS 311"
---
Implemented and analyzed classic algorithms and data structures, including linked lists, heaps, sorting algorithms, shortest paths (Dijkstra, Bellman-Ford) and dynamic programming problems. Documented correctness proofs, and runtime analysis. This strengthened my problem solving skills and theoretical understanding of algorithms. This allowed me demonstrate the ability to translate theory into efficient code while analyzing performace tradeoffs.

Here is an example of some psuedocde I had to learn how to implement to solve a shortest paths problem

DIJKSTRA(G, w, s)
  INITIALIZE-SINGLE-SOURCE(G, s)
  S = ∅
  Q = G.V
  while Q ≠ ∅
    u = EXTRACT-MIN(Q)
    S = S ∪ {u}
    for each vertex v in G.Adj[u]
      RELAX(u, v, w)

