# Copying Structures in C

## Overview

This project demonstrates how to **copy one structure variable to another** in C. Structures of the same type can be assigned directly using the assignment operator (`=`), which copies all member values from one structure to another.

The program creates a structure, initializes it with values, copies it to another structure variable, and displays the copied data.

---

## Concepts Covered

- Structures (`struct`)
- Structure initialization
- Structure assignment
- Copying structures
- Character arrays (strings)
- Member access using the dot (`.`) operator
- Formatted output using `printf()`

---

## Project Description

The program defines a structure named `myStructure` containing:

- An integer member (`myNum`)
- A character member (`myLetter`)
- A string member (`myString`)

A structure variable `s1` is initialized with values. Another structure variable `s2` is created, and all data from `s1` is copied into `s2` using the assignment operator.

---

## Structure Definition

```c
struct myStructure {
    int myNum;
    char myLetter;
    char myString[30];
};
```

This structure groups different data types into a single user-defined data type.

---

## Structure Initialization

```c
struct myStructure s1 = {13, 'B', "Some text"};
```

The structure `s1` is initialized with predefined values.

---

## Copying the Structure

```c
struct myStructure s2;

s2 = s1;
```

The assignment operator copies all members of `s1` into `s2`, including the integer, character, and string.

---

## Sample Output

```text
13 B Some text
```

---

## Learning Outcomes

- Understanding structure assignment
- Copying one structure to another
- Working with multiple structure variables
- Accessing copied structure members
- Using structures to organize related data

---

## Real-World Applications

- Student Record Management
- Employee Information Systems
- Inventory Management
- Banking Applications
- Embedded Systems
- Database Record Handling

---

## Time Complexity

```text
O(1)
```

Structure assignment is performed in constant time for fixed-size structures.

---

## Space Complexity

```text
O(1)
```

A fixed amount of memory is allocated for the structure variables.

---

## Key Takeaway

Structures of the same type can be copied directly using the assignment operator (`=`). This copies all member values, making it an efficient way to duplicate structured data.

---

## Author

**Amrutha D N**
