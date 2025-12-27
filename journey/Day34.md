# Day 34 — 27th Dec 2025

## 💻 Web Development

### 🔸 Pre-React JavaScript Revision
Focused on revising core JavaScript concepts required before moving fully into React:

- Variables (`var`, `let`, `const`)
- Scope & hoisting
- Functions and arrow functions
- Arrays & objects manipulation
- Callbacks and basic async understanding
- How JavaScript concepts map to React usage

---

## 🧠 DSA Progress

### 🔸 Problem Solved  
**88. Merge Sorted Array**

---

### 🔸 Problem Summary  
Given two sorted arrays `nums1` and `nums2`, merge them into a single sorted array **in-place** inside `nums1`.

---

### 🔸 Approach Used — Two Pointer (From End)
- Used three pointers:
  - One at the end of valid elements in `nums1`
  - One at the end of `nums2`
  - One at the end of total array size
- Compared elements from the back and placed the larger one at the end
- Avoided extra space

---

### 🔸 Key Concepts Practiced
- Two-pointer technique
- In-place array modification
- Handling edge cases (`m = 0`, `n = 0`)
- Efficient merging logic

---

### 🔸 Time & Space Complexity
- **Time Complexity:** `O(m + n)`
- **Space Complexity:** `O(1)`

---

### 🔸 Pattern Used
- Two pointers
- In-place merge
