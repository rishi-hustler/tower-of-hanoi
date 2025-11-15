# Tower of Hanoi (Java)

## 📌 Overview

The **Tower of Hanoi** is a classic **recursion problem** that involves moving a stack of disks from one rod to another, following specific rules.

### Rules:

1. Only **one disk** can be moved at a time
2. A **larger disk cannot be placed on a smaller disk**
3. Only the **top disk** of any rod can be moved

---

## 🚀 Algorithm Used

**Recursion**

### Strategy:

To move `n` disks from Source to Destination:

1. Move `n-1` disks from Source to Auxiliary
2. Move the largest disk from Source to Destination
3. Move `n-1` disks from Auxiliary to Destination

This recursive breakdown continues until the base case (`n = 1`) is reached.

---

## 🧮 Time and Space Complexity

* **Time Complexity:** `O(2ⁿ)`
* **Space Complexity:** `O(n)` (recursion stack)

---

## 🛠️ Requirements

* Java 8 or later
* Any Java IDE or command-line environment

---

## 📂 Project Structure

```
TowerOfHanoi.java
README.md
```

---

## ▶️ How to Run

1. Compile the program:

   ```bash
   javac TowerOfHanoi.java
   ```
2. Run the program:

   ```bash
   java TowerOfHanoi
   ```

---

## ⌨️ Sample Input

```
Enter number of disks: 3
```

---

## ✅ Sample Output

```
Steps to solve Tower of Hanoi:
Move disk 1 from A to C
Move disk 2 from A to B
Move disk 1 from C to B
Move disk 3 from A to C
Move disk 1 from B to A
Move disk 2 from B to C
Move disk 1 from A to C
```

---

## 🧠 Key Concepts

* Recursion
* Divide and Conquer
* Stack behavior (call stack)
* Problem decomposition

---

## 🔧 Customization Ideas

* Count total number of moves
* Visualize disk movement
* Add step numbering
* Limit output for large `n`

---

## 📚 Applications

* Understanding recursion
* Algorithm analysis
* Mathematical problem solving
* Interview preparation

---

## 📝 License

Free to use for academic, learning, and interview preparation.

