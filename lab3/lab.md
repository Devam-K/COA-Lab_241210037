# COA Lab Experiment

## 4-Bit Ripple Carry Adder and Delay Analysis using Basic Gates in Logisim

---

## Aim

To design and implement a **4-bit Ripple Carry Adder (RCA)** using basic logic gates in Logisim and to study the propagation delay associated with ripple carry addition.

---

## Software Used

Logisim

---

## Theory

### Ripple Carry Adder

A Ripple Carry Adder is a combinational circuit used to perform binary addition of multi-bit numbers. It is constructed by connecting multiple full adders in series.

* Each full adder adds corresponding bits of two numbers along with a carry input
* The carry output of each stage is passed to the next stage
* This sequential propagation of carry is called the "ripple" effect

For a 4-bit RCA:

* Four full adders are connected in cascade
* Inputs: ( A_3A_2A_1A_0 ), ( B_3B_2B_1B_0 ), and initial carry ( C_0 )
* Outputs: Sum bits ( S_3S_2S_1S_0 ) and final carry ( C_4 )

---

### Full Adder using Basic Gates

A full adder can be implemented using basic gates (AND, OR, XOR):

* Sum:
  [
  S = A \oplus B \oplus C_{in}
  ]

* Carry:
  [
  C_{out} = (A \cdot B) + (C_{in} \cdot (A \oplus B))
  ]

---

### Propagation Delay in Ripple Carry Adder

The main disadvantage of an RCA is its delay.

* Each full adder must wait for the carry from the previous stage
* Total delay is proportional to the number of bits

If delay of one full adder is ( t ), then:
[
\text{Total Delay} = n \cdot t
]

For a 4-bit RCA:
[
\text{Total Delay} = 4t
]

This delay is called **carry propagation delay**.

---

## Components Used

* XOR gates
* AND gates
* OR gates
* Input pins
* Output pins
* Wires and connectors

---

## Circuit Description

### Full Adder Design

* Each full adder is built using basic gates
* XOR gates are used for sum calculation
* AND and OR gates are used to generate carry

---

### 4-Bit Ripple Carry Adder

* Four full adders are connected in series
* Carry output of each stage is connected to carry input of the next stage
* First stage takes external carry input ( C_0 )
* Final stage produces carry output ( C_4 )

---

## Procedure

* Open Logisim and create a new circuit
* Design a full adder using XOR, AND, and OR gates
* Verify the full adder using all input combinations
* Replicate the full adder four times
* Connect them in cascade to form a 4-bit ripple carry adder
* Provide inputs using input pins
* Observe outputs (sum and carry) using output pins
* Test the circuit with different binary inputs

---

## Observations

* The sum output is correct for all input combinations
* Carry propagates sequentially from least significant bit to most significant bit
* Delay increases as carry moves through each stage

---

## Result

The 4-bit Ripple Carry Adder was successfully implemented using basic gates in Logisim. The propagation delay due to carry ripple was observed and verified.

---

## Conclusion

* Ripple Carry Adder is simple and easy to implement
* The major limitation is propagation delay due to sequential carry transfer
* Delay increases linearly with the number of bits
* This highlights the need for faster adders in high-speed systems

---


