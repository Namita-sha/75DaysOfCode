# Day 26 — SQL Practice (19th Dec 2025)
## 🧠 DSA Progress

### 🔸 Problem Solved  
**29. Divide Two Integers**

---

### 🔸 Problem Summary  
Given two integers `dividend` and `divisor`, divide them **without using multiplication, division, or modulo operators**.  
The result must be **truncated toward zero** and stay within **32-bit signed integer range**.

---

### 🔸 Approach Used
- Used **bit manipulation + subtraction**
- Converted both numbers to **positive long values**
- Repeatedly subtracted the largest possible multiple of divisor using **left shifts**
- Applied sign at the end
- Handled **overflow edge case** (`INT_MIN / -1`)

---

### 🔸 Key Concepts Practiced
- Bitwise left shift (`<<`)
- Doubling technique for fast subtraction
- Handling integer overflow
- Sign management using XOR logic

---

### 🔸 Algorithm (High Level)
1. Handle overflow case separately  
2. Determine the sign of the result  
3. Convert numbers to positive values  
4. Use bit shifting to subtract largest multiples efficiently  
5. Apply sign and return result  

---

### 🔸 Time & Space Complexity
- **Time Complexity:** `O(log n)`
- **Space Complexity:** `O(1)`

---

### 🔸 Pattern Used
- Bit Manipulation
- Binary Search–like doubling technique

## 🗄️ SQL Progress

### 🔸 Problem Solved  
**1280. Students and Examinations**

---

### 🔸 Problem Summary  
Given three tables:
- **Students**
- **Subjects**
- **Examinations**

Each student takes every subject, but may or may not attend the exam.  
The task is to find **how many times each student attended each subject exam**, including cases where the student did **not attend at all (count = 0)**.

The final result must:
- Include **all students × all subjects**
- Show `0` where no exam was attended
- Be ordered by `student_id` and `subject_name`

---

### 🔸 Approach Used
- Generated all possible **student–subject combinations**
- Used **LEFT JOIN** with the `Examinations` table
- Applied **COUNT()** to count exam attendance
- Used **GROUP BY** to aggregate results correctly
- Ensured missing records return `0` instead of `NULL`



