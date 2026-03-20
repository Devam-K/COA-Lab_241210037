# 🧪 Computer Organization & Architecture Lab  
## Experiment 1: Design of Basic Logic Gates using Universal Gates  

---

## 🎯 Aim  
To design and implement basic logic gates (AND, OR, NOT) using **universal gates** (NAND and NOR gates).

---

## 📚 Theory  

Logic gates are the fundamental building blocks of digital systems. The basic gates include:  
- AND Gate  
- OR Gate  
- NOT Gate  

**Universal Gates** are gates that can be used to implement any Boolean function. These include:  
- NAND Gate  
- NOR Gate  

Using combinations of NAND or NOR gates, we can construct all basic logic gates.

---

## 🧰 Apparatus / Requirements  
- Digital Logic Trainer Kit / Simulation Software  
- NAND and NOR ICs (e.g., 7400, 7402)  
- Connecting wires  
- Power supply (5V)  

---

## ⚙️ Procedure  

### Part A: Using NAND Gates  

1. **NOT Gate using NAND**  
   - Connect both inputs of NAND together.  
   - Output gives complement of input.

2. **AND Gate using NAND**  
   - Use two NAND gates.  
   - First NAND gives complement of AND, second NAND inverts it.

3. **OR Gate using NAND**  
   - Apply De Morgan’s theorem.  
   - Use three NAND gates to achieve OR operation.

---

### Part B: Using NOR Gates  

1. **NOT Gate using NOR**  
   - Connect both inputs together.  

2. **OR Gate using NOR**  
   - Use two NOR gates.  

3. **AND Gate using NOR**  
   - Use three NOR gates with De Morgan’s theorem.

---

## 🔢 Truth Tables  

### AND Gate  
| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   0    |
| 1 | 0 |   0    |
| 1 | 1 |   1    |

### OR Gate  
| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   1    |

### NOT Gate  
| A | Output |
|---|--------|
| 0 |   1    |
| 1 |   0    |

---

## 📐 Circuit Diagrams  
*(Draw the following in your lab notebook or simulation tool)*  
- NAND-based NOT, AND, OR  
- NOR-based NOT, AND, OR  

---

## 📊 Observations  
- The outputs obtained match the expected truth tables.  
- NAND and NOR gates successfully implement all basic logic gates.  

---

## ✅ Result  
Basic logic gates (AND, OR, NOT) were successfully designed and implemented using **universal gates (NAND and NOR)**.

---
