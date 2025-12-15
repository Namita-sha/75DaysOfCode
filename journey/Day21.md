## 🧠 DSA Progress

### 🔸 Problem Solved  
**136. Single Number**

#### 🔸 Problem Summary  
Given an array of integers where every element appears **twice except one**, find the element that appears only once.

---

#### 🔸 Approach Used — Brute Force (Nested Loop)

- Traversed the array element by element
- For each element, counted how many times it appears in the array
- If the count is exactly `1`, that element is the required answer

---

#### 🔸 Algorithm (Simple Explanation)
1. Loop through the array using index `i`
2. Pick the current element `nums[i]`
3. Initialize a counter `cnt = 0`
4. Loop through the array again using index `j`
5. If `nums[j] == nums[i]`, increment `cnt`
6. If `cnt == 1`, return the element
7. If no such element is found, return `-1`

---

#### 🔸 Time & Space Complexity
- **Time Complexity:** `O(n²)`  
  (due to nested loops)
- **Space Complexity:** `O(1)`  
  (no extra data structures used)

---

#### 🔸 Pattern Used
- Brute Force
- Frequency counting using nested traversal



