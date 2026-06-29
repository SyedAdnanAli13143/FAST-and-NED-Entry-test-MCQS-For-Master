# Object-Oriented Programming (5 Questions)

> 🔁 This overlaps heavily with FAST's Specialization Area (file `05`, section B) in the FAST University Prep folder — studying both together saves time.

**Q1.** Which of these is **NOT** one of the four main pillars of OOP?
A) Inheritance  B) Polymorphism  C) Compilation  D) Encapsulation
**Answer: C) Compilation**

**Q2.** A class meant only to be a base for other classes, and never instantiated directly, is called:
A) Concrete class  B) Abstract class  C) Static class  D) Final class
**Answer: B) Abstract class**

**Q3.** Which concept lets a subclass provide its own version of a method already defined in its parent class?
A) Overloading  B) Overriding  C) Encapsulation  D) Casting
**Answer: B) Overriding**

**Q4.** Method **Overloading** means:
A) Same method name with different parameter lists, within the same class  B) Same method name and same parameters, redefined in a child class  C) Different method names with the same parameters  D) Using more memory than needed
**Answer: A)**

**Q5.** A variable or method that belongs to the class itself (shared by all objects) rather than to one specific object is called:
A) Instance member  B) Static member  C) Private member  D) Local member
**Answer: B) Static member**

**Q6.** Which access modifier allows access from the same class **and** from its subclasses, but not from unrelated outside classes?
A) Public  B) Private  C) Protected  D) Static
**Answer: C) Protected**

**Q7.** An "interface" in OOP typically:
A) Contains fully implemented methods only  B) Defines a contract of methods that implementing classes must provide  C) Can be instantiated directly like a normal class  D) Is the same thing as a constructor
**Answer: B)**

**Q8.** Which OOP concept best describes "a Car HAS-A Engine" (one object containing another as a part)?
A) Inheritance  B) Composition  C) Polymorphism  D) Overriding
**Answer: B) Composition**

**Q9.** Which OOP concept best describes "a Dog IS-A Animal"?
A) Inheritance  B) Composition  C) Encapsulation  D) Overloading
**Answer: A) Inheritance**

**Q10.** What is the purpose of a **constructor**?
A) To destroy an object  B) To initialize an object's data when it is created  C) To copy one class into another  D) To compile the program
**Answer: B)**

**Q11.** Can a single class have more than one constructor, each with a different parameter list?
A) No, never  B) Yes — this is called constructor overloading  C) Only inside abstract classes  D) Only if all methods are static
**Answer: B)**

**Q12.** Which best describes **Encapsulation**?
A) Bundling data and methods together while restricting direct access to internal details  B) Creating many unrelated classes  C) Writing the same function repeatedly  D) Using only global variables
**Answer: A)**

**Q13.** **Polymorphism** allows:
A) A single interface/method name to represent different underlying behaviours depending on the object  B) Only one class to exist per program  C) Variables to silently change data type at runtime, in every language  D) Classes to delete themselves automatically
**Answer: A)**

**Q14.** What does `this` (or `self` in some languages) refer to inside a class's method?
A) The class definition itself  B) The current object instance the method is operating on  C) A global variable  D) The parent class
**Answer: B)**

**Q15.** Which statement about a **private** class member is true?
A) It can be accessed from anywhere in the program  B) It can only be accessed within the class where it's declared  C) It can only be accessed by subclasses  D) It is automatically static
**Answer: B)**

---

## Quick-recall summary

| Pillar | One-line meaning |
|---|---|
| Encapsulation | Hide data, expose only what's needed |
| Abstraction | Show essential features, hide implementation detail |
| Inheritance | Child class reuses/extends parent class ("IS-A") |
| Polymorphism | Same name, different behaviour depending on object |

| Term | Meaning |
|---|---|
| Overloading | Same method name, different parameters, **same** class |
| Overriding | Child class redefines a parent's method |
| Constructor | Runs when object is created |
| Destructor | Runs when object is destroyed |
| Composition | "HAS-A" relationship (object contains another object) |
