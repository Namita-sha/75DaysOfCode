# Day 30 — 23rd Dec 2025

## 🧠 DSA Progress

### 🔸 Problem Solved  
**153. Find Minimum in Rotated Sorted Array**

---

### 🔸 Problem Summary  
Given a **sorted array that has been rotated**, find the **minimum element** in the array.  
The solution must run in **O(log n)** time.

---

### 🔸 Approach Used — Binary Search

- Leveraged the fact that the array consists of **two sorted halves**
- At least one half is always sorted
- Compared middle element with right boundary to decide which half contains the minimum

---

### 🔸 Key Logic
- If `nums[mid] > nums[right]`  
  → Minimum lies in the **right half**
- Else  
  → Minimum lies in the **left half (including mid)**
- Continue until search space reduces to one element

---

### 🔸 Algorithm (High Level)
1. Initialize `low = 0`, `high = n - 1`
2. While `low < high`:
   - Compute `mid`
   - Compare `nums[mid]` with `nums[high]`
   - Move `low` or `high` accordingly
3. Return `nums[low]`

---

### 🔸 Time & Space Complexity
- **Time Complexity:** `O(log n)`
- **Space Complexity:** `O(1)`

---

### 🔸 Pattern Used
- Binary Search on Rotated Sorted Array
- Divide and Conquer
- Search Space Reduction
