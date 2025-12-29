# Day 36 — 29th Dec 2025

## 🧠 DSA Progress

### 🔸 Revision: Array & String Basics
- Revised basic array operations (traversal, indexing, updates)
- Revised string operations and character handling

---

## 🧩 DSA Patterns — Conceptual Study

### 1️⃣ Prefix Sum
Prefix Sum is used to efficiently calculate the sum of elements in a subarray.

- Preprocess the array to build a cumulative sum array
- Each index stores sum of elements from start to that index
- Allows answering range sum queries in constant time

**Key Formula:**
```
sum(i, j) = prefix[j] - prefix[i - 1]
```
---

### 2️⃣ Two Pointers
The Two Pointers pattern uses two indices to traverse the array efficiently.

- Commonly used in sorted arrays
- Helps find pairs or optimize brute-force solutions
- Moves pointers based on condition comparison

📌 Reduces time complexity from `O(n²)` to `O(n)` in many problems

---

### 3️⃣ Sliding Window
Sliding Window is used for problems involving contiguous subarrays or substrings.

- Maintain a window of elements
- Expand or shrink the window based on constraints
- Efficient alternative to nested loops

📌 Common in substring and subarray problems

---

### 4️⃣ Fast & Slow Pointers
Used mainly for cycle detection problems.

- One pointer moves slowly
- Another pointer moves faster
- If a cycle exists, both pointers eventually meet

📌 Commonly used in linked list problems

---

## 🌐 System Design — Conceptual Overview

### 🔸 GraphQL (Overview)
- Allows clients to request **exact data they need**
- Avoids over-fetching and under-fetching
- Single query can replace multiple REST API calls
- Trade-offs: harder caching, more server processing

---

### 🔸 Databases (Overview)
- Databases store and manage large-scale application data
- Server communicates with database to fetch/store information
- Backbone of modern applications

---

### 🔸 SQL vs NoSQL

**SQL Databases**
- Structured schema
- ACID properties
- Strong consistency
- Used in banking and transactional systems

**NoSQL Databases**
- Flexible schema
- Highly scalable
- Optimized for performance
- Includes key-value, document, graph, and column stores

📌 Many modern systems use **both** together

---

### 🔸 Vertical Scaling
- Increasing CPU/RAM of a single server
- Simple but limited
- Causes single point of failure

---

### 🔸 Horizontal Scaling
- Adding more servers
- Improves scalability and fault tolerance
- Requires load balancing

---

### 🔸 Load Balancers
- Distribute traffic across multiple servers
- Improve availability and performance
- Common algorithms:
  - Round Robin
  - Least Connections
  - IP Hashing

---

### 🔸 Database Indexing
- Speeds up read queries
- Acts like a book index
- Improves SELECT performance
- Slows down writes if overused

---

### 🔸 Replication
- One primary database handles writes
- Multiple replicas handle reads
- Improves read scalability and availability

---

## 🖥️ Operating Systems (OS)

### 🔸 Topics Studied
- Memory Management
- Free Space Management
- Paging
- Segmentation

---

## 💻 Web Development — React & JavaScript

### 🔸 React Topics Covered
- Understanding Props
- Mini projects using Props
- Styling React components with CSS
- Introduction to Tailwind CSS
- UI design project
- Working with functions inside components

