# Day 27 — 20th Dec 2025

## 🧠 DSA Progress

### 🔸 Problem Attempted  
**144. Binary Tree Preorder Traversal**

---

### 🔸 Reason for Solving  
Today I intentionally tried a **Tree problem** to:
- Step outside arrays/strings
- Get a first hands-on feel of tree traversal
- Understand recursion flow in hierarchical data structures

---

### 🔸 Approach Used — Recursive Preorder Traversal

**Preorder order:**  
➡️ Root → Left → Right

---

### 🔸 Algorithm (Simple Explanation)
1. If the current node is `NULL`, return
2. Add the node’s value to the result
3. Recursively traverse the left subtree
4. Recursively traverse the right subtree

---

### 🔸 Key Concepts Learned
- Tree node structure (`val`, `left`, `right`)
- Recursive traversal using helper function
- Base case handling (`nullptr`)
- Difference between **array traversal** and **tree traversal**
- How recursion naturally fits tree problems

---

### 🔸 Time & Space Complexity
- **Time Complexity:** `O(n)`  
  (each node visited once)
- **Space Complexity:** `O(h)`  
  (recursion stack, where `h` = height of tree)

---

### 🔸 Pattern Used
- Tree Traversal
- Recursion
- DFS (Depth First Search)

