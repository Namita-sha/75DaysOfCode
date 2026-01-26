# Day 58 — 26th Jan 2026

## 🎯 Focused DSA Practice Day

Today was dedicated to **linked list fundamentals** and understanding a classic interview trick question.

---

## 🧠 DSA Progress

### 🔸 Problem Solved  
**237. Delete Node in a Linked List** (Medium)

---

### 🔸 Problem Summary  
You are given **only the node to be deleted**, not the head of the linked list.  
The node is guaranteed **not to be the last node**.

The task is to delete the given node such that:
- The value no longer exists in the list
- List size reduces by one
- Order of remaining nodes is preserved

---

### 🔸 Key Insight / Trick
- Since we don’t have access to the previous node:
  - Copy the value of the **next node** into the current node
  - Skip the next node by updating the pointer

---

### 🔸 Concepts Practiced
- Linked list manipulation
- Pointer reassignment
- Understanding problem constraints deeply
- Interview trick questions

---

### 🔸 Time & Space Complexity
- **Time Complexity:** `O(1)`
- **Space Complexity:** `O(1)`

---

### 🔸 Pattern Used
- Linked List — pointer overwrite technique

