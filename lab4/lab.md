# Experiment 4  
## Debugging C Programs using GDB (Pointers, Stacks, Queues, and Linked Lists)

---

## 1. Objective

To study and use the GNU Debugger (GDB) for debugging C programs, with emphasis on analyzing pointer behavior and debugging dynamic data structures such as stacks, queues, and linked lists.

---

## 2. Introduction to GDB

The GNU Debugger (GDB) is a command-line debugging tool used to analyze and control the execution of programs written in languages such as C and C++. It allows the programmer to:

- Pause execution using breakpoints  
- Execute code step-by-step  
- Inspect and modify variable values  
- Examine memory and registers  
- Analyze function calls and program flow  

GDB works with debugging symbols generated during compilation, enabling mapping between source code and machine instructions.

---

## 3. Setup and Installation of GDB

### 3.1 Checking if GDB is Installed

```bash
gdb --version
