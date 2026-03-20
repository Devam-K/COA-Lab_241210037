# Computer Organization & Architecture Lab  
## Experiment 1: Design of Basic Logic Gates using Universal Gates (Using Multisim)

---

## Aim  
To design and simulate basic logic gates (AND, OR, NOT) using **universal gates (NAND and NOR)** in **NI Multisim**.

---

## Software Requirements  
- NI Multisim (Electronic Circuit Simulation Software)
---

## Theory  

Logic gates are the basic building blocks of digital circuits. The fundamental gates are:  
- AND Gate  
- OR Gate  
- NOT Gate  

**Universal Gates** such as NAND and NOR can be used to implement any Boolean function.

Using **De Morgan’s Theorem**, we can construct all basic gates using only NAND or only NOR gates.

---

## Procedure  

## Part A: Design using Basic Gates (Direct Implementation in Multisim)

1. Open **NI Multisim** and create a new circuit.  
2. From the component library, place the following **basic gates**:  
   - AND Gate  
   - OR Gate  
   - NOT Gate  

3. Perform the following implementations:

   - **AND Gate**  
     - Connect two input switches (A, B) to the AND gate.  
     - Connect output to an LED or logic probe.  

   - **OR Gate**  
     - Connect two input switches (A, B) to the OR gate.  
     - Observe output using LED/probe.  

   - **NOT Gate**  
     - Connect a single input switch (A) to the NOT gate.  
     - Observe inverted output.  

4. Run the simulation.  
5. Toggle input switches and verify outputs with the truth tables.

### Part B: Using NAND Gates in Multisim  

1. Open **NI Multisim** and create a new design.  
2. Place **NAND gates** from the component library.  
3. Implement the following:

   - **NOT Gate using NAND**  
     - Connect both inputs of a NAND gate together.  

   - **AND Gate using NAND**  
     - Use two NAND gates.  
     - First NAND performs NAND operation.  
     - Second NAND acts as inverter.

   - **OR Gate using NAND**  
     - Use three NAND gates based on De Morgan’s theorem.  

4. Add input switches and output indicators (LEDs or probes).  
5. Run the simulation and verify outputs.

---

## Truth Tables  

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

## Observations  

- The simulated outputs match the expected truth tables.  
- NAND and NOR gates successfully implement all basic logic gates.  
- Multisim provides accurate and real-time verification of logic behavior.

---

## Result  

Basic logic gates (AND, OR, NOT) were successfully **designed and simulated using universal gates (NAND and NOR) in NI Multisim**.

---

## Precautions  

- Ensure correct selection of logic gate components in Multisim.  
- Verify all connections before running simulation.  
- Use proper input sources (logic switches) and output indicators.  

---
