# Experiment 4  
## Debugging C Programs using GDB (Pointers, Stacks, Queues, and Linked Lists)

---

## Objective

To study and apply the GNU Debugger (GDB) for debugging C programs, particularly those involving pointers and dynamic data structures such as stacks, queues, and linked lists.

---

## Background

Debugging is an essential step in software development for detecting and correcting errors. The GNU Debugger (GDB) is a widely used tool that allows controlled execution of programs, inspection of variables, and analysis of memory.

Pointers play a crucial role in C programming as they store memory addresses and are used in dynamic memory allocation. Improper handling of pointers may result in segmentation faults, memory leaks, or undefined behavior.

Stacks and queues are linear data structures. A stack operates on the Last In First Out (LIFO) principle, while a queue follows the First In First Out (FIFO) principle. Linked lists consist of nodes connected through pointers, enabling efficient dynamic memory usage.

---

## Experiment Description

C programs implementing pointers, stacks, queues, and linked lists were written and debugged using GDB. The programs were compiled using the `-g` flag to include debugging information.

### Compilation
```bash
gcc -g program.c -o program
