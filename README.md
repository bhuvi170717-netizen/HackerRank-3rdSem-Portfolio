# HackerRank 3rd Semester Portfolio

A collection of algorithmic problem-solving solutions completed as part of **Portfolio Building — B25CS0311, Activity 8**.

This repository demonstrates fundamental problem-solving skills involving arrays, matrices, strings, vectors, hash maps, and algorithmic complexity analysis using **C++**.

---

## 🎯 Activity Objectives

This activity focuses on:

* Developing algorithmic problem-solving skills using C++.
* Working with arrays, matrices, strings, vectors, and hash maps.
* Understanding efficient algorithm design.
* Analyzing Time and Space Complexity.
* Practicing problems on the HackerRank platform.
* Building a structured and documented programming portfolio.

---

## 👨‍💻 HackerRank Profile

**HackerRank:** [View My HackerRank Profile](https://www.hackerrank.com/bhuvi170717)

---

## 📚 Problems Completed

| # | Problem                                          | Topic                     | Time Complexity | Space Complexity | Status     |
| - | ------------------------------------------------ | ------------------------- | --------------- | ---------------- | ---------- |
| 1 | [Diagonal Difference](Diagonal-Difference/)   | 2D Arrays / Matrices      | O(N)            | O(1)             | ✅ Accepted |
| 2 | [Dynamic Array](Dynamic-Array/)               | Data Structures / Vectors | O(Q)            | O(N + Q)         | ✅ Accepted |
| 3 | [Time Conversion](Time-Conversion/)           | Strings & Logic           | O(1)            | O(1)             | ✅ Accepted |
| 4 | [Compare the Triplets](Compare-the-Triplets/) | Basic Implementation      | O(1)            | O(1)             | ✅ Accepted |
| 5 | [Sparse Arrays](Sparse-Arrays/)               | Hash Maps / Strings       | O(N + Q)        | O(N)             | ✅ Accepted |

---

## 🧠 Problem Solutions

### 1. Diagonal Difference

**Concept:** Matrix traversal and diagonal sums.

The solution traverses the matrix once and simultaneously calculates the primary and secondary diagonal sums.

```text
Primary diagonal:   arr[i][i]
Secondary diagonal: arr[i][N - 1 - i]
```

The absolute difference between the two sums is returned.

**Complexity:**

* Time: `O(N)`
* Auxiliary Space: `O(1)`

[View Solution →](Diagonal-Difference/solution.cpp)

---

### 2. Dynamic Array

**Concept:** Dynamic sequences, vectors, and XOR indexing.

The solution maintains `N` dynamic sequences using C++ vectors. For each query, the sequence index is calculated using:

```text
(x ^ lastAnswer) % N
```

Type 1 queries append values, while Type 2 queries retrieve an element and update `lastAnswer`.

**Complexity:**

* Time: `O(Q)` average/amortized for processing the queries
* Space: `O(N + Q)` in the worst case

[View Solution →](Dynamic-Array/solution.cpp)

---

### 3. Time Conversion

**Concept:** String manipulation and 12-hour to 24-hour time conversion.

The solution extracts the hour and AM/PM indicator and handles the special cases of `12 AM` and `12 PM`.

**Complexity:**

* Time: `O(1)`
* Space: `O(1)`

[View Solution →](Time-Conversion/solution.cpp)

---

### 4. Compare the Triplets

**Concept:** Element-wise comparison and score tracking.

Each of the three corresponding scores is compared. A point is awarded to Alice or Bob depending on which score is greater.

**Complexity:**

* Time: `O(1)`
* Space: `O(1)`

[View Solution →](Compare-the-Triplets/solution.cpp)

---

### 5. Sparse Arrays

**Concept:** Frequency counting using a hash map.

An `unordered_map` stores the frequency of every string in the input list. Each query can then be answered through a direct average-case hash-map lookup.

**Complexity:**

* Time: `O(N + Q)` average case
* Space: `O(N)`

[View Solution →](Sparse-Arrays/solution.cpp)

---

## 📊 Complexity Summary

| Problem              |                   Time |    Space |
| -------------------- | ---------------------: | -------: |
| Diagonal Difference  |                   O(N) |     O(1) |
| Dynamic Array        | O(Q) average/amortized | O(N + Q) |
| Time Conversion      |                   O(1) |     O(1) |
| Compare the Triplets |                   O(1) |     O(1) |
| Sparse Arrays        |       O(N + Q) average |     O(N) |

> **Note:** Complexity for hash-map operations assumes average-case `O(1)` insertion and lookup.

---

## 📸 HackerRank Submission Evidence

Screenshots of successful HackerRank submissions are stored in the [`screenshots`](screenshots/) directory.

| Problem              | Evidence                                                |
| -------------------- | ------------------------------------------------------- |
| Diagonal Difference  | [View Screenshot](Screenshots/diagonal-difference.png)  |
| Dynamic Array        | [View Screenshot](Screenshots/dynamic-array.png)        |
| Time Conversion      | [View Screenshot](Screenshots/time-conversion.png)      |
| Compare the Triplets | [View Screenshot](Screenshots/compare-the-triplets.png) |
| Sparse Arrays        | [View Screenshot](Screenshots/sparse-arrays.png)        |

---

## 🏆 HackerRank Badge

The required HackerRank skill badge evidence will be included here.

**Required milestone:** 3-Star Badge in Problem Solving or C++/Java/Python.

![HackerRank Badge](screenshots/badge.png)

---

## 📁 Repository Structure

```text
HackerRank-3rdSem-Portfolio/
│
├── README.md
│
├── 01-Diagonal-Difference/
│   └── solution.cpp
│
├── 02-Dynamic-Array/
│   └── solution.cpp
│
├── 03-Time-Conversion/
│   └── solution.cpp
│
├── 04-Compare-the-Triplets/
│   └── solution.cpp
│
├── 05-Sparse-Arrays/
│   └── solution.cpp
│
└── screenshots/
    ├── diagonal-difference.png
    ├── dynamic-array.png
    ├── time-conversion.png
    ├── compare-the-triplets.png
    ├── sparse-arrays.png
    └── badge.png
```

---

## 📈 Skills Demonstrated

* C++ Programming
* Array Manipulation
* Matrix Traversal
* Dynamic Arrays
* STL Vectors
* String Manipulation
* Hash Maps
* Bitwise XOR
* Algorithmic Problem Solving
* Time Complexity Analysis
* Space Complexity Analysis

---

## 🎓 Course Information

**Course:** Portfolio Building
**Course Code:** B25CS0311
**Semester:** 3rd Semester B.Tech — Computer Science & Engineering
**Activity:** Activity 8 — HackerRank Algorithmic Problem-Solving & Portfolio Integration
**Language:** C++

---

## 🔗 Links

* **HackerRank:** [My HackerRank Profile](https://www.hackerrank.com/bhuvi170717)
* **GitHub Repository:** [HackerRank-3rdSem-Portfolio](https://github.com/bhuvi170717-netizen/HackerRank-3rdSem-Portfolio)

---

## 📌 Status

**Activity 8:** Completed

**Problems:** 5/5
**Language:** C++
**Platform:** HackerRank
