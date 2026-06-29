# Specialization Area (30% of your score) — the section you didn't know had a name

This is **Object-Oriented Programming + Data Structures & Algorithms + basic programming logic**. Confirmed real because FAST lists "Object Oriented Programming" and "Data Structures and Algorithms" as prerequisite courses for both MS(AI) and MS(DS), and explicitly waives the non-credit "Applied Programming" course for students who do well on this admission test.

> 🔁 **This overlaps almost completely with NED's OOP (file `04`) and Design & Analysis of Algorithms (file `06`) sections** in the NED University Prep folder. Studying this file well prepares you for both universities at once.

---

## A. Programming Fundamentals & Logic Tracing

**Q1.** What does this pseudocode print?
```
x = 5
y = 10
if x > y:
    print("A")
else:
    print("B")
```
A) A  B) B  C) Nothing  D) Error
**Answer: B) B** — 5 is not greater than 10, so the else branch runs.

**Q2.** What is printed?
```
total = 0
for i = 1 to 5:
    total = total + i
print(total)
```
A) 10  B) 15  C) 20  D) 25
**Answer: B) 15** — 1+2+3+4+5 = 15

**Q3.** What is the final value of x?
```
x = 2
x = x * x
x = x + 1
```
A) 4  B) 5  C) 6  D) 9
**Answer: B) 5** — 2×2=4, then 4+1=5

**Q4.** Which loop structure guarantees the loop body executes **at least once**?
A) for loop  B) while loop  C) do-while loop  D) None of these
**Answer: C) do-while loop** — it checks the condition *after* running the body.

**Q5.** What does this pseudocode compute?
```
n = 5
fact = 1
for i = 1 to n:
    fact = fact * i
```
A) Sum of 1 to n  B) Factorial of n  C) n squared  D) n cubed
**Answer: B) Factorial of n** — 5! = 120

**Q6.** A variable declared inside a function, inaccessible outside it, is called a:
A) Global variable  B) Local variable  C) Static variable  D) Constant
**Answer: B) Local variable**

**Q7.** What is an "infinite loop"?
A) A loop that never executes  B) A loop whose condition never becomes false  C) A loop that runs exactly once  D) A loop with no body
**Answer: B)**

---

## B. Object-Oriented Programming (OOP)

**Q1.** What is **Encapsulation**?
A) Hiding internal details and exposing only what's necessary  B) Creating many classes  C) Using loops efficiently  D) Writing comments
**Answer: A)**

**Q2.** Which OOP feature lets a child class acquire the properties/behaviour of a parent class?
A) Polymorphism  B) Inheritance  C) Encapsulation  D) Abstraction
**Answer: B) Inheritance**

**Q3.** "One function/method name behaving differently depending on input" describes:
A) Inheritance  B) Polymorphism  C) Encapsulation  D) Abstraction
**Answer: B) Polymorphism**

**Q4.** Hiding implementation details and showing only essential features to the user describes:
A) Inheritance  B) Polymorphism  C) Abstraction  D) Overloading
**Answer: C) Abstraction**

**Q5.** What is a **Class**?
A) An instance of an object  B) A blueprint/template for creating objects  C) A function inside an object  D) A loop structure
**Answer: B)**

**Q6.** What is an **Object**?
A) A blueprint for a class  B) An instance of a class  C) A type of loop  D) A variable type
**Answer: B)**

**Q7.** What is the difference between **Overloading** and **Overriding**?
A) Overloading = same method name with different parameters in the same class; Overriding = redefining a parent class method in a child class
B) Overloading only happens in loops; Overriding only in arrays
C) They are exactly the same thing
D) Overloading happens in the child class; Overriding happens in the same class
**Answer: A)**

**Q8.** A special method automatically called when an object is **created** is a:
A) Destructor  B) Constructor  C) Accessor  D) Mutator
**Answer: B) Constructor**

**Q9.** A special method automatically called when an object is **destroyed** is a:
A) Constructor  B) Destructor  C) Overloaded method  D) Static method
**Answer: B) Destructor**

**Q10.** Which access modifier allows a member to be accessed **only within its own class**?
A) Public  B) Private  C) Protected  D) Global
**Answer: B) Private**

**Q11.** An **abstract class** is best described as:
A) A class that cannot be instantiated directly and may contain unimplemented (abstract) methods
B) A class with no methods at all
C) A class that can never be inherited
D) A class with only static methods
**Answer: A)**

---

## C. Data Structures Basics

**Q1.** Which data structure follows **Last In, First Out (LIFO)**?
A) Queue  B) Stack  C) Array  D) Linked List
**Answer: B) Stack**

**Q2.** Which data structure follows **First In, First Out (FIFO)**?
A) Stack  B) Queue  C) Tree  D) Graph
**Answer: B) Queue**

**Q3.** In a singly linked list, each node contains:
A) Only data  B) Data and a pointer to the next node  C) Data and pointers to both next and previous nodes  D) Only a pointer
**Answer: B)**

**Q4.** What is the main advantage of a linked list over an array?
A) Faster random access  B) Dynamic size — easy insertion/deletion without shifting elements  C) Always uses less memory  D) Always sorted
**Answer: B)**

**Q5.** A tree where each node has **at most two children** is called a:
A) Binary tree  B) Graph  C) Stack  D) Linked list
**Answer: A)**

**Q6.** Which operation adds an element to the **top** of a stack?
A) Enqueue  B) Push  C) Dequeue  D) Pop
**Answer: B) Push**

**Q7.** Which operation removes an element from the **front** of a queue?
A) Push  B) Pop  C) Enqueue  D) Dequeue
**Answer: D) Dequeue**

**Q8.** A graph where edges have a direction (A→B is different from B→A) is called a:
A) Undirected graph  B) Directed graph  C) Binary tree  D) Stack
**Answer: B) Directed graph**

---

## D. Algorithms & Complexity (Big-O)

**Q1.** What does **Big-O notation** describe?
A) The exact runtime of an algorithm in seconds  B) How an algorithm's runtime/memory use grows as input size grows  C) The number of lines of code  D) The programming language used
**Answer: B)**

**Q2.** Time complexity of accessing an array element by its index:
A) O(1)  B) O(n)  C) O(log n)  D) O(n²)
**Answer: A) O(1)**

**Q3.** Worst-case time complexity of **Linear Search**:
A) O(1)  B) O(log n)  C) O(n)  D) O(n²)
**Answer: C) O(n)**

**Q4.** Worst-case time complexity of **Binary Search** on a sorted array:
A) O(1)  B) O(log n)  C) O(n)  D) O(n²)
**Answer: B) O(log n)**

**Q5.** Binary Search requires the input to be:
A) Unsorted  B) Sorted  C) A linked list only  D) Of even length
**Answer: B) Sorted**

**Q6.** Worst-case time complexity of **Bubble Sort**:
A) O(n)  B) O(n log n)  C) O(n²)  D) O(log n)
**Answer: C) O(n²)**

**Q7.** Which of these has the best average-case time complexity?
A) Bubble Sort  B) Selection Sort  C) Merge Sort  D) Insertion Sort
**Answer: C) Merge Sort — O(n log n)**, vs O(n²) for the other three.

**Q8.** Which algorithm design strategy does **Merge Sort** use?
A) Greedy  B) Divide and Conquer  C) Dynamic Programming  D) Brute Force
**Answer: B) Divide and Conquer**

**Q9.** A recursive function must always have a ___ to avoid infinite recursion.
A) Loop  B) Base case  C) Global variable  D) Pointer
**Answer: B) Base case**

**Q10.** Which of these grows **fastest** (i.e. is least efficient) as input size n increases?
A) O(log n)  B) O(n)  C) O(n log n)  D) O(n²)
**Answer: D) O(n²)**

---

## E. Bonus: Basic Databases (lower priority — only if time allows)

**Q1.** A column (or set of columns) that uniquely identifies each row in a table is a:
A) Foreign key  B) Primary key  C) Index  D) Schema
**Answer: B) Primary key**

**Q2.** SQL stands for:
A) Structured Query Language  B) Simple Query Logic  C) Sequential Query Language  D) Structured Question Language
**Answer: A)**

**Q3.** Which SQL command retrieves data from a table?
A) INSERT  B) SELECT  C) UPDATE  D) DELETE
**Answer: B) SELECT**

