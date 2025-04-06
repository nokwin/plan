# 📌 FAANG Interview Study Plan

## 🚀 Introduction
Hey there! 👋 My name is **Stepan**, and I am a **Front-End Engineer at Microsoft** with around **8 years of experience** (Level 62 at Microsoft). 

This document outlines my structured plan to prepare for **FAANG interviews**, covering **algorithms, system design, and behavioral interviews**. Follow along as I document my journey! 🏆

---

## 📌 Study Overview

| Section               | Details |
|----------------------|---------|
| **Algorithm Practice** | Solve **5 easy, 5 medium, and 2 hard** tasks per topic (**~1 week per topic**). |
| **System Design**     | Spend **~1 week per topic**. |
| **Behavioral Interview** | Prepare **~3 stories per day**. |

---

## 📚 Algorithm Core 
### 💡 How to Approach Algorithm Problems
1. **Understand the Problem** – Read carefully, clarify requirements, and identify constraints.
2. **Identify the Pattern** – Recognize problem type based on common techniques.
3. **Plan the Approach** – Start with a brute-force solution, then optimize.
4. **Implement the Code** – Follow a structured plan, keeping it modular.
5. **Optimize & Test** – Analyze time/space complexity and test edge cases.

### 🔹 Key Algorithm Topics
- **Sliding Window** – Used for **subarrays, substrings, sequences**.

📖 **Links:**  
- [Mastering Sliding Window Techniques](https://medium.com/@rishu__2701/mastering-sliding-window-techniques-48f819194fd7)  

#### 🟢 Easy  
- [Longest Harmonious Subsequence](https://leetcode.com/problems/longest-harmonious-subsequence/) – Frequency map-based sliding window  
- [Maximum Number of Vowels in a Substring of Given Length](https://leetcode.com/problems/maximum-number-of-vowels-in-a-substring-of-given-length/) – Fixed size sliding window  

#### 🟡 Medium  
- [Maximum Sum of Distinct Subarrays With Length K](https://leetcode.com/problems/maximum-sum-of-distinct-subarrays-with-length-k/) – Fixed + HashSet  
- [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) – Classic dynamic sliding window  
- [Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/) – Shrinking window when sum ≥ target  
- [Fruits Into Baskets](https://leetcode.com/problems/fruit-into-baskets/) – At most 2 types of fruit, like 2 distinct chars  
- [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/) – Max count + allowed replacements  
- [Subarrays with K Different Integers](https://leetcode.com/problems/subarrays-with-k-different-integers/) – Tricky: requires inclusion-exclusion technique  
- [Number of Substrings Containing All Three Characters](https://leetcode.com/problems/number-of-substrings-containing-all-three-characters/) – Maintain all 3 types in shrinking window  

#### 🔴 Hard  
- [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) – Deque-based (advanced technique)  
- [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) – Track char count, shrink while valid  
- [Count Subarrays With Median K](https://leetcode.com/problems/count-subarrays-with-median-k/) – Mapping median to balance and prefix sum  

💡 **Opinion:** One of the easiest algorithmic techniques, but mastering optimizations can be tricky. 🚀  




- **Two Pointers** – Efficient for **sorted arrays, linked lists**.
- **Fast & Slow Pointers (Floyd’s Cycle Detection)** – Detect **cycles**.
- **Merge Intervals** – Handle **overlapping ranges**.
- **Binary Search** – Efficient searching in **sorted arrays**.
- **Bit Manipulation** – Useful for **binary number operations**.
- **Backtracking** – Explore multiple possibilities **recursively**.
- **Dynamic Programming (DP)** – Solve problems with **overlapping subproblems**.
- **Greedy Algorithms** – Optimal **local choices** leading to a global solution.
- **Graph Traversal (DFS & BFS)** – Solve **grid/tree problems**.
- **Union-Find (Disjoint Set)** – Handle **connectivity problems**.
- **Heap (Priority Queue)** – Find **smallest/largest** element efficiently.
- **Prefix Sum & Difference Arrays** – Optimize **subarray sum queries**.
- **Topological Sorting** – Solve problems with **dependencies (DAG)**.
- **Trie (Prefix Tree)** – Useful for **autocomplete, dictionary words**.
- **Monotonic Stack / Queue** – Solve **next/previous greater elements**.
- **Segment Tree & Fenwick Tree** – Handle **efficient range queries**.

---

## 📌 JavaScript Core
### 🔹 Closures & Lexical Scope
✔️ Private variables, memoization, callbacks.

### 🔹 Promises & Async/Await
✔️ Handling async operations, API calls, and event listeners.

### 🔹 Memoization & Caching
✔️ Store results to optimize performance (e.g., Fibonacci, API calls).

### 🔹 Event Loop & Microtasks
✔️ Understanding **call stack, task queue, microtask queue**.

### 🔹 Functional Programming
✔️ Pure functions, higher-order functions (`map`, `filter`, `reduce`).

### 🔹 Currying & Partial Application
✔️ Modular function transformations for better reuse.

### 🔹 Prototypes & `this`
✔️ JavaScript's **prototype-based inheritance**.

### 🔹 Debouncing & Throttling
✔️ Improve performance for **scrolling, resizing** events.

### 🔹 Generators & Iterators
✔️ Useful for **lazy evaluation, pagination**.

### 🔹 WeakMap & WeakSet
✔️ **Memory-efficient** storage with garbage collection support.

### 🔹 Tail Call Optimization (TCO)
✔️ Optimize recursive functions to avoid **stack overflow**.

---

## 🏗️ System Design Topics
### 🔹 Internet & HTTP Basics
✔️ HTTP vs. HTTPS, REST vs. GraphQL, Status Codes, CORS, DNS, API Rate Limiting.

### 🔹 Accessibility (A11Y) & UX
✔️ WCAG Guidelines, ARIA Roles, Screen Readers, Color Contrast.

### 🔹 Performance Optimization
✔️ Page Load Optimization, Lazy Loading, Database Indexing, Load Balancing.

### 🔹 Security in System Design
✔️ XSS, CSRF, SQL Injection, OAuth, JWT, HTTPS, DDoS Protection.

### 🔹 Scalability & Load Balancing
✔️ Horizontal vs. Vertical Scaling, Database Sharding, Microservices.

### 🔹 Database Design & Optimization
✔️ SQL vs. NoSQL, Indexing, Partitioning, Event Sourcing.

### 🔹 APIs & Communication Patterns
✔️ REST, GraphQL, gRPC, WebSockets, API Gateway.

### 🔹 Microservices & Event-Driven Architecture
✔️ Kafka, RabbitMQ, Pub/Sub, Docker, Kubernetes.

### 🔹 DevOps & CI/CD
✔️ GitHub Actions, Jenkins, Terraform, Monitoring (Grafana, ELK Stack).

### 🔹 Design Patterns & Best Practices
✔️ SOLID Principles, Singleton, Factory, Observer, CAP Theorem.

---

## 📌 System Design Practice Tasks
- [ ] **Chat**
- [ ] **Typeahead Search**
- [ ] **Data Table**
- [ ] **Infinite Scroll**
- [ ] **Zoom/Teams**
- [ ] **Component Library**
- [ ] **Poll Widget**
- [ ] **News Feed**
- [ ] **Stock Service**
- [ ] **Amazon Shop**
- [ ] **Netflix**
- [ ] **Trello**

---

## 🔥 Final Notes
This plan serves as a **guide to mastering FAANG interviews**. Consistency is key! If you find this helpful, feel free to **star ⭐ this repository** and follow my progress.

Let's crush FAANG interviews together! 🚀
