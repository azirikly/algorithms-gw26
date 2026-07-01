---
layout: page
title: Course Modules
nav_order: 3
description: Course schedule and modules for CS 3212.
---

# Course Schedule & Modules
{:.no_toc}

---

## Module 1: Core Foundations, Sorting & Tree Structures

### Week 1: Introduction, Efficiency & Code Profiling
- Introduction to algorithmic thinking and problem-solving framework
- Formal definitions and intuition behind Big-O, Big-Omega, and Big-Theta notation
- Best-case, worst-case, and average-case complexity analysis

### Week 2: Divide-and-Conquer & Comparison Sorting
- The divide-and-conquer strategy template
- Internal mechanics and trace of Mergesort and Quicksort
- Solving recurrence relations using the Master Theorem and recursion trees
- The information-theoretic lower bound (Ω(n log n)) for comparison-based sorting

### Week 3: Heaps, Heapsort & Linear-Time Sorting
- Representing binary trees efficiently using arrays
- Building and maintaining Max-Heaps and Min-Heaps
- The Heapsort algorithm structure
- Breaking the comparison sorting barrier using Bucketsort

### Week 4: Ordered Search & Balanced Binary Trees
- Review of Binary Search Trees (BST) insertion and lookup
- The mechanics of deleting nodes from a BST
- Structural imbalance in trees and its impact on runtime
- Restoring height balance invariants using structural rotations in AVL Trees

### Week 5: Advanced Search Structures: Multiway & Self-Adjusting Trees
- Multiway search trees (B-Trees and B+ Trees) used in database disk storage
- Self-adjusting binary search trees (Splay Trees)
- Introduction to amortized analysis (evaluating the average cost of operations over time)

---

## Module 2: Hashing, Strings & Graph Algorithms

### Week 6: Key Lookup, Hashing & Tries
- Direct addressing vs. hashing frameworks
- Designing effective hash functions and handling data collisions
- Digital search trees and Tries for rapid prefix processing

### Week 7: Pattern Search & String Matching
- The string search problem definition
- The Rabin-Karp algorithm using rolling hashes
- The Knuth-Morris-Pratt (KMP) algorithm using prefix functions to skip redundant shifts

### Week 8: Graph Foundations & Traversals
- Graph representations (Adjacency Matrices vs. Adjacency Lists)
- Breadth-First Search (BFS) for shortest paths in unweighted graphs
- Depth-First Search (DFS) mechanics and edge classifications
- Topological Sorting for ordering tasks with dependencies in Directed Acyclic Graphs (DAGs)

---

## Module 3: Optimization & Sequence Modeling

### Week 9: Minimum Spanning Trees & Shortest Paths
- The greedy algorithm design paradigm and greedy choice invariants
- Kruskal's algorithm (utilizing the Union-Find data structure with path compression)
- Prim's algorithm for building minimum spanning trees
- Dijkstra's algorithm for single-source shortest paths on weighted graphs

### Week 10: Network Flow & Dynamic Programming Foundations
- Flow networks, capacities, cuts, and the Edmonds-Karp Max-Flow algorithm
- Introduction to Dynamic Programming (DP) core principles
- Overlapping subproblems and optimal substructure properties
- Memoization (top-down caching) vs. Tabulation (bottom-up table building) via the 0-1 Knapsack problem

### Week 11: Advanced Dynamic Programming & Sequence Alignment
- Measuring similarity between sequences using DP
- Longest Common Subsequence (LCS) tracking
- Edit Distance (Levenshtein Distance) for text correction and sequence matching
- Finding shortest paths between all pairs of nodes using the Floyd-Warshall algorithm

### Week 12: Special Topic — Algorithms in Natural Language Processing & Health Informatics
- Utilizing pattern search and sequence alignment to parse unstructured clinical notes and social media data
- Modeling token sequences and handling missing/noisy data fields
- Decoding optimal hidden states using the Viterbi Algorithm over sequence models

---

## Module 4: Intractability & Advanced Paradigms

### Week 13: Solution Spaces, Local Search & Intro to Complexity
- Finding high-quality solutions when exact mathematical solutions take too long
- Exploring solution spaces using local neighborhoods and randomized walks
- Greedy Local Search and Simulated Annealing meta-heuristics
- Defining what makes a problem computationally hard (P vs. NP complexity classes)

### Week 14: Approximation, Randomized Algorithms & Course Wrap-Up
- Designing Approximation Algorithms with verifiable performance guarantees to cope with hard problems
- Understanding the difference between Las Vegas and Monte Carlo randomized algorithms
- Course synthesis and algorithmic paradigm selection matrix
