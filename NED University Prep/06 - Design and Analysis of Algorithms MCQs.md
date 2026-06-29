# Design & Analysis of Algorithms (5–10 Questions) — Complexity of Algorithms

> 🔁 Overlaps with FAST's Specialization Area (file `05`, section D) in the FAST University Prep folder.

## A. Time Complexity Basics

**Q1.** What is the time complexity of accessing an element in an array by its index?
A) O(1)  B) O(n)  C) O(log n)  D) O(n²)
**Answer: A) O(1)**

**Q2.** Worst-case time complexity of **Linear Search**:
A) O(1)  B) O(log n)  C) O(n)  D) O(n²)
**Answer: C) O(n)**

**Q3.** Worst-case time complexity of **Binary Search** (on a sorted array):
A) O(1)  B) O(log n)  C) O(n)  D) O(n²)
**Answer: B) O(log n)**

**Q4.** Worst-case time complexity of **Bubble Sort**:
A) O(n)  B) O(n log n)  C) O(n²)  D) O(log n)
**Answer: C) O(n²)**

**Q5.** Average-case time complexity of **Merge Sort**:
A) O(n)  B) O(n log n)  C) O(n²)  D) O(log n)
**Answer: B) O(n log n)**

**Q6.** Average-case time complexity of **Quick Sort**, and its worst case:
A) Average O(n log n), Worst O(n²)  B) Average O(n²), Worst O(n log n)  C) Both always O(n log n)  D) Both always O(n²)
**Answer: A)** — Quick Sort is usually fast (O(n log n)) but degrades to O(n²) on already-sorted/poorly-chosen-pivot inputs.

## B. Algorithm Design Paradigms

**Q7.** Which paradigm solves a problem by breaking it into smaller subproblems of the **same type**, solving each independently, and combining the results?
A) Greedy  B) Divide and Conquer  C) Dynamic Programming  D) Backtracking
**Answer: B) Divide and Conquer** (e.g. Merge Sort, Binary Search)

**Q8.** Which paradigm makes the **locally optimal choice at each step**, hoping it leads to a globally optimal solution?
A) Greedy  B) Divide and Conquer  C) Dynamic Programming  D) Backtracking
**Answer: A) Greedy**

**Q9.** Which paradigm solves problems by breaking them into **overlapping subproblems** and storing/reusing results to avoid recomputing them?
A) Greedy  B) Divide and Conquer  C) Dynamic Programming  D) Backtracking
**Answer: C) Dynamic Programming**

**Q10.** Which paradigm tries possible solutions step by step and **abandons ("backtracks")** any path that can't lead to a valid solution?
A) Greedy  B) Divide and Conquer  C) Dynamic Programming  D) Backtracking
**Answer: D) Backtracking**

## C. Complexity Concepts

**Q11.** "Best case", "Worst case", and "Average case" complexity describe:
A) Different programming languages  B) How an algorithm performs under different kinds of input  C) The number of bugs in the code  D) The size of the source code file
**Answer: B)**

**Q12.** "Space complexity" refers to:
A) The time taken to run an algorithm  B) The amount of memory an algorithm uses as input size grows  C) The number of programmers needed  D) The number of test cases written
**Answer: B)**

**Q13.** Which of these growth rates is the **slowest-growing** (most efficient) as input size n increases?
A) O(n)  B) O(n²)  C) O(log n)  D) O(n log n)
**Answer: C) O(log n)**

**Q14.** A recurrence relation like `T(n) = 2T(n/2) + O(n)` typically describes the time complexity of which kind of algorithm?
A) Linear Search  B) Merge Sort (Divide and Conquer)  C) Bubble Sort  D) A constant-time operation
**Answer: B)**

**Q15.** Which sorting algorithm is "in-place," generally has worst case O(n²), but is very fast and efficient on small or nearly-sorted datasets?
A) Merge Sort  B) Insertion Sort  C) Heap Sort  D) Radix Sort
**Answer: B) Insertion Sort**

**Q16.** What is the time complexity of searching for an element in a **balanced** Binary Search Tree?
A) O(1)  B) O(log n)  C) O(n)  D) O(n²)
**Answer: B) O(log n)**

**Q17.** Which of these correctly orders complexities from **fastest/best** to **slowest/worst** for large n?
A) O(n²) < O(n log n) < O(n) < O(log n) < O(1)
B) O(1) < O(log n) < O(n) < O(n log n) < O(n²)
C) O(n) < O(1) < O(n²) < O(log n)
D) They are all equal in practice
**Answer: B)**

---

## Quick-recall summary

| Algorithm | Time Complexity |
|---|---|
| Array index access | O(1) |
| Linear Search | O(n) |
| Binary Search | O(log n) |
| Bubble / Selection / Insertion Sort (worst) | O(n²) |
| Merge Sort | O(n log n) always |
| Quick Sort | O(n log n) average, O(n²) worst |
| BST search (balanced) | O(log n) |

| Paradigm | Key idea |
|---|---|
| Divide and Conquer | Split into same-type subproblems, combine results |
| Greedy | Best choice right now, every step |
| Dynamic Programming | Reuse solutions to overlapping subproblems |
| Backtracking | Try, fail, undo, try a different path |
