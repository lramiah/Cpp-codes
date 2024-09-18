# C++ Course Assignments - Problem Descriptions

This repository contains the problem statements for my C++ course assignments. The problems cover a range of topics, including data structures, smart pointers, recursion, functors, and more. Below is an overview of each assignment's requirements.

## Table of Contents
- [Assignment 1: Doubly Linked List](#assignment-1-doubly-linked-list)
- [Assignment 2: STL Manipulation](#assignment-2-stl-manipulation)
- [Assignment 3: Constructor, Assignment, Destructor](#assignment-3-constructor-assignment-destructor)
- [Assignment 4: Recursion and Binary Trees](#assignment-4-recursion-and-binary-trees)
- [Assignment 5: Smart Pointers](#assignment-5-smart-pointers)
- [Assignment 6: Functors](#assignment-6-functors)
- [Assignment 7: Templates](#assignment-7-templates)

---

### Assignment 1: Doubly Linked List

- **Problem**: Implement a doubly linked list class (`DLL`) with member functions for printing forward and backward, sorting a sublist, and merging two sublists. The `Merge` operation must be done in-place without using any extra data structures or creating new nodes.
- **Concepts**: Doubly linked list, in-place sorting, and merging.
  
[Problem Statement](./HW1_Doubly_Linked_List.pdf)

---

### Assignment 2: STL Manipulation

- **Problem**: Implement a student database system using Standard Template Library (STL) containers such as `map`, `list`, and `tuple`. The database should support adding and removing students and courses, calculating GPAs, and ensuring that all courses within a semester are sorted by name.
- **Concepts**: STL containers, GPA calculation, operator overloading.
  
[Problem Statement](./HW2_STL_Manipulation.pdf)

---

### Assignment 3: Constructor, Assignment, Destructor

- **Problem**: Implement a `DBclass` to manage a student’s academic records. This class should support operations like adding courses, calculating GPAs, and removing the first element in the database. You must implement the constructor, copy constructor, move constructor, copy assignment, move assignment, and destructor.
- **Concepts**: Rule of Five, object management, deep copying.
  
[Problem Statement](./HW3_Constuctor_Assignment_Destructor.pdf)

---

### Assignment 4: Recursion and Binary Trees

- **Problem**: Implement a binary tree class (`tree`) with functions for building a full binary tree, traversing the tree (inorder, preorder, postorder), and calculating the maximum and minimum values in the tree. Additionally, the tree should be restructured based on specific conditions related to the difference between the maximum and minimum values in the subtrees.
- **Concepts**: Recursion, binary trees, tree traversal, tree restructuring.
  
[Problem Statement](./HW4_Recursion.pdf)

---

### Assignment 5: Smart Pointers

- **Problem**: Implement a `triangle` class that uses smart pointers (`shared_ptr` and `weak_ptr`). The class should include constructors, destructors, copy and move semantics, and a function to return the first three rows of the triangle. No raw pointers or extra helper functions are allowed.
- **Concepts**: Smart pointers, memory management, copy and move semantics.
  
[Problem Statement](./HW5_Smart_Pointers.pdf)

---

### Assignment 6: Functors

- **Problem**: Implement a `LinkedList` class and various sorting functions. The class should support sorting using different comparison criteria through functors and lambdas. Additionally, handle data structures like `map` and `set` for comparison, hashing, and printing.
- **Concepts**: Functors, lambda expressions, sorting, STL data structures.
  
[Problem Statement](./HW6_Functors.pdf)

---

### Assignment 7: Templates

- **Problem**: Implement a `bag` class template using a doubly linked list, supporting initialization from a list, copy and move operations, and sorting with a custom functor. The `Sort` function should perform bubble sort and remove duplicates. The assignment requires overloading the `<<` operator for printing the contents of the `bag`.
- **Concepts**: Templates, doubly linked lists, sorting, operator overloading.
  
[Problem Statement](./HW7_Templates.pdf)

---

## How to Use
This repository contains only the problem statements for the assignments. Please check the corresponding files to get the detailed requirements.
